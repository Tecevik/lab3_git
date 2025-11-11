<div align="center">

# 🦖 ЛАБОРАТОРНАЯ РАБОТА №3
## Система контроля версий Git

<img src="https://media.tenor.com/4EhUju6UJtEAAAAi/grrr-rawr.gif" width="300" alt="Welcome Dinosaur">

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnu-bash&logoColor=white)

**«Покорил Git как настоящий динозавр!»** 🦖

</div>

---

## 📋 О ПРОЕКТЕ

**ИСУ:** 505068  
**Студент:** Шипицын Артём-Жан Александрович  
**Группа:** J3116  
**Предмет:** Архитектура вычислительных систем

Лабораторная работа по освоению системы контроля версий Git. В ходе работы изучены основные концепции ветвления, слияния, разрешения конфликтов и управления историей коммитов.

## 🎯 ВЫПОЛНЕННЫЕ ЗАДАНИЯ

### ✅ Основные задания (1-8)
- **Задание 1-2:** Работа с коммитами в main ветке
- **Задание 3:** Создание коммитов в ветке hf_tests  
- **Задание 4:** Сравнение коммитов и создание diff.txt
- **Задание 5:** Откат к историческим коммитам
- **Задание 6:** Выполнение rebase между ветками
- **Задание 7:** Слияние feature-веток с конфликтами
- **Задание 8:** Создание release-ветки

### ✅ Дополнительное задание (-1)
- Создание аккаунта на GitHub
- Оформление репозитория и профиля
- Создание README.md

## 🏗 СТРУКТУРА РЕПОЗИТОРИЯ

```
lab3_repo_505068/
├── secrets.txt     # Основной файл для работы
├── diff.txt        # Сравнение коммитов
├── history.txt     # Полная история репозитория
├── README.md       # Документация (этот файл)
└── .git/           # Git метаданные
```

## 📊 СТАТИСТИКА

![GitHub Last Commit](https://img.shields.io/github/last-commit/Tecevik/lab3_repo_505068)
![GitHub Repo Size](https://img.shields.io/github/repo-size/Tecevik/lab3_repo_505068)
![GitHub Issues](https://img.shields.io/github/issues/Tecevik/lab3_repo_505068)

**Ветки:** 12  
**Коммитов:** 25+  
**Конфликтов разрешено:** 4+  
**Навыков Git получено:** 100% ✅

## 🚀 КАК ЗАПУСТИТЬ

```bash
# Клонировать репозиторий
git clone https://github.com/Tecevik/lab3_repo_505068.git

# Перейти в директорию
cd lab3_repo_505068

# Просмотреть историю коммитов
git log --oneline --graph --all
```

## 📚 ПОЛЕЗНЫЕ ССЫЛКИ

[![Git Documentation](https://img.shields.io/badge/📚_Git_Docs-orange?style=for-the-badge)](https://git-scm.com/doc)
[![GitHub](https://img.shields.io/badge/🐙_GitHub_Repo-black?style=for-the-badge)](https://github.com/Tecevik/lab3_repo_505068)

---

<div align="center">

**Лабораторная работа успешно завершена!** 🎓  

<img src="https://media.giphy.com/media/3o7abKhOpu0NwenH3O/giphy.gif" width="200" alt="Success">

</div>


## 📊 Git History Graph

Вот граф истории коммитов, демонстрирующий выполнение всех заданий лабораторной работы:

```bash
* b3bcf74 (HEAD -> main, origin/main) Add graph
* 4ac67e6 коммит ридмишки
* 5cf6608 коммит ридмишки
* 24a934d коммит ридмишки
* 9182acc Add diff.txt
* 10390d3 Add history.txt
* e22d4c9 Add history.txt
*   e0d276b (origin/release, release) коммит фичи2 в ветку мейн
|\
| * add93e6 (origin/feature2, feature2) feature2 change
* |   98cf669 коммит фичи1 в ветку мейн
|\ \
| * | 5a6f3cf (origin/feature1, feature1) feature1 change
| |/
* |   1043375 (origin/hf_tests, hf_tests) коммит временной ветки temp_reset
|\ \
| * | 9bff367 (origin/temp_reset, temp_reset) коммит теормина после отката к 3-ему коммиту
* | | 3f16ed7 коммит не теормина
* | | 389909b коммит теормина
| |/
|/|
* | cd5b816 (origin/server_last, origin/pr_feature, origin/hotfix, origin/gguf, origin/backend_metal, origin/backend_cuda, server_last, pr_feature, hotfix, gguf, backend_metal, backend_cuda) add secrets.txt 5
* | e337a44 add secrets.txt 4
|/
* 4eacd02 add secrets.txt 3
* 2f71813 add secrets.txt 2
* 3a3d186 add secrets.txt 1
* e969f47 init
```

### 🔍 Анализ графа:
- **Ветвление и слияние** - видны merge коммиты (задание 7)
- **Rebase** - линейная история после задания 6  
- **Множество веток** - feature1, feature2, hf_tests, release и др.
- **Разрешение конфликтов** - отражено в истории коммитов
