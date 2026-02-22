# backend_test_homework

**[English](#english)** | **[Русский](#русский)**

---

<a id="english"></a>

## English

### Description

A test homework assignment from the [Yandex Practicum](https://practicum.yandex.ru/) backend Python development course. The repository is forked from [yandex-praktikum/backend_test_homework](https://github.com/yandex-praktikum/backend_test_homework).

The task is to fork the repository, write a Python script (`program.py`) that runs without errors, and make sure all automated tests pass.

### Project Structure

```
backend_test_homework/
├── .gitignore          — Git ignore rules
├── README.md           — Project documentation
├── program.py          — Main script (homework solution)
├── pytest.ini          — Pytest configuration
└── test_program.py     — Automated tests
```

### How It Works

- `program.py` — the main script that prints a message to the console.
- `test_program.py` — automated tests that verify:
  - `program.py` and `README.md` exist in the repository root.
  - `program.py` runs without errors.
- `pytest.ini` — Pytest configuration with verbose output.

### Requirements

- Python 3.x
- pytest

### Running

Run the script:

```bash
python program.py
```

Run the tests:

```bash
pytest
```

### Author

[Artem Leonov](https://github.com/artemleonich)

---

<a id="русский"></a>

## Русский

### Описание

Тестовое домашнее задание курса бэкенд-разработки на Python от [Яндекс Практикума](https://practicum.yandex.ru/). Репозиторий форкнут из [yandex-praktikum/backend_test_homework](https://github.com/yandex-praktikum/backend_test_homework).

Задание: форкнуть репозиторий, написать Python-скрипт (`program.py`), который запускается без ошибок, и убедиться, что все автоматические тесты проходят.

### Структура проекта

```
backend_test_homework/
├── .gitignore          — Правила игнорирования для Git
├── README.md           — Документация проекта
├── program.py          — Основной скрипт (решение задания)
├── pytest.ini          — Конфигурация Pytest
└── test_program.py     — Автоматические тесты
```

### Как это работает

- `program.py` — основной скрипт, выводящий сообщение в консоль.
- `test_program.py` — автоматические тесты, которые проверяют:
  - Наличие файлов `program.py` и `README.md` в корне репозитория.
  - Запуск `program.py` без ошибок.
- `pytest.ini` — конфигурация Pytest с подробным выводом.

### Требования

- Python 3.x
- pytest

### Запуск

Запуск скрипта:

```bash
python program.py
```

Запуск тестов:

```bash
pytest
```

### Автор

[Артём Леонов](https://github.com/artemleonich)
