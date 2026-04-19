# lab03

Лабораторная работа N3 по курсу "Технологии и методы программирования".

## Содержимое

- `TASK.md` - текст задания и домашней работы
- `REPORT.md` - отчет
- `formatter_lib` - статическая библиотека `formatter`
- `formatter_ex_lib` - статическая библиотека `formatter_ex`
- `solver_lib` - библиотека решения квадратного уравнения
- `hello_world_application` - пример использования `formatter_ex`
- `solver_application` - приложение с использованием `formatter_ex` и `solver`

## Сборка

```bash
cmake -S . -B _build
cmake --build _build
./_build/hello_world_application/hello_world
```
