# REPORT

## Laboratory work III

В репозитории выполнены задания лабораторной работы по CMake и домашняя работа.

## Что сделано

1. Добавлены исходные файлы для библиотек `formatter`, `formatter_ex` и `solver`.
2. Созданы отдельные `CMakeLists.txt`:
   - для `formatter_lib`
   - для `formatter_ex_lib`
   - для `solver_lib`
   - для приложений `hello_world_application` и `solver_application`
3. Создан корневой `CMakeLists.txt` для сборки проекта целиком.
4. В репозиторий добавлены задание (`TASK.md`) и отчет (`REPORT.md`).

## Проверка

Проект рассчитан на сборку командами:

```bash
cmake -S . -B _build
cmake --build _build
```

## Ссылки

- Репозиторий: `https://github.com/kanadya07/lab03`
- Задание: `TASK.md`
