# Отчет по лабораторной работе №3

## Тема работы

Изучение системы автоматизации сборки CMake.

## Цель работы

Научиться собирать проект с помощью CMake и оформить домашнее задание с
библиотеками и приложениями.

## Ход работы

### 1. Подготовка репозитория

Сначала я создала репозиторий `lab03` и перенесла в него проект из предыдущей
лабораторной работы.

Пример команд:

```bash
git clone https://github.com/kanadya07/lab02.git lab03
cd lab03
git remote remove origin
git remote add origin https://github.com/kanadya07/lab03.git
```

### 2. Создание основного файла сборки

Потом я создала основной файл `CMakeLists.txt`, в котором подключила все части
проекта.

Пример команд:

```bash
touch CMakeLists.txt
git add CMakeLists.txt
git commit -m "Добавила основной CMakeLists.txt"
```

### 3. Оформление библиотек

Дальше по домашнему заданию я оформила библиотеки:

1. `formatter_lib`
2. `formatter_ex_lib`
3. `solver_lib`

Для каждой папки был добавлен свой `CMakeLists.txt`.

Команды:

```bash
touch formatter_lib/CMakeLists.txt
touch formatter_ex_lib/CMakeLists.txt
touch solver_lib/CMakeLists.txt
```

### 4. Оформление приложений

После этого я оформила два приложения:

1. `hello_world_application`
2. `solver_application`

Для них тоже были добавлены файлы `CMakeLists.txt`.

```bash
touch hello_world_application/CMakeLists.txt
touch solver_application/CMakeLists.txt
```

### 5. Проверка сборки

После настройки файлов сборки проект можно собирать через CMake.

Команды:

```bash
cmake -S . -B _build
cmake --build _build
```

### 6. Добавление отчета и задания

В конце я добавила в репозиторий текст задания и отчет.

```bash
git add TASK.md REPORT.md
git commit -m "Добавила задание и отчет"
git push origin master
```

## Что находится в репозитории

1. `TASK.md`
2. `REPORT.md`
3. `CMakeLists.txt`
4. папки с библиотеками
5. папки с приложениями

## Вывод

Во время выполнения этой лабораторной работы я научилась описывать сборку
проекта в CMake, подключать библиотеки и приложения и собирать проект через
команды терминала.

## Ссылка на репозиторий

https://github.com/kanadya07/lab03
