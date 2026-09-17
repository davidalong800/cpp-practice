# cpp-practice

Решённые задачи по C++ с разных сайтов. Здесь я собираю всё, что решаю сам: код задачи, ссылка на неё и короткая заметка о том, что оказалось новым.

## Структура

```
cpp-practice/
├── README.md          ← этот файл
├── LICENSE            ← лицензия MIT
├── .gitignore         ← что не выкладывается на GitHub
└── hackerrank/        ← задачи с HackerRank
    └── Conditional_Statements.cpp
```

Правило простое: **папка верхнего уровня — сайт** (`hackerrank/`, потом при желании `leetcode/`, `codewars/`). Так добавление нового сайта — это одна новая папка, а не переименование всего репозитория.

Имена файлов пишу через `_`, без пробелов: `Conditional_Statements.cpp`. Первой строкой файла — ссылка на задание:

```cpp
// HackerRank — Conditional Statements
// https://www.hackerrank.com/challenges/c-tutorial-conditional-if-else
```

## Решённые задачи

| Сайт | Задача | Файл | Что нового |
|---|---|---|---|
| HackerRank | Conditional Statements | `hackerrank/Conditional_Statements.cpp` | условие + массив строк |

## Стиль

- решение копирую вместе с данным каркасом (HackerRank часто даёт готовый `main`), меняю только то, что требуется в задаче;
- вверху файла — ссылка на задачу и название.

## Лицензия

Распространяется по [лицензии MIT](LICENSE).
