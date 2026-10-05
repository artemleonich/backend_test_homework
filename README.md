<p align="center">
  <img src=".github/assets/banner.svg" width="100%" alt="Backend · Первое задание" />
</p>

# Backend · Первое задание

Минимальный Python-проект для знакомства с GitHub и автоматическими проверками.

**Учебный проект** · Python · pytest  
[Русский](#about) · [English](#english) · [Профиль](https://github.com/artemleonich)

<a id="about"></a>

## О проекте

Вводное задание курса бэкенд-разработки на Python от [Яндекс Практикума](https://practicum.yandex.ru/). Решение — скрипт `program.py`, который выводит сообщение «Я домашка».

Репозиторий основан на [yandex-praktikum/backend_test_homework](https://github.com/yandex-praktikum/backend_test_homework). Цель задания — освоить форк репозитория, добавить запускаемый скрипт и пройти проверку.

## Запуск

```bash
git clone https://github.com/artemleonich/backend_test_homework.git
cd backend_test_homework
python3 program.py
```

Для тестов установите pytest в отдельное окружение:

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install pytest
python -m pytest
```

В Windows PowerShell окружение активируется командой `.venv\Scripts\Activate.ps1`.

## Что проверяют тесты

`test_program.py` проверяет наличие `program.py` и `README.md` в корне репозитория, затем импортирует скрипт. Это небольшое вводное упражнение; отдельного приложения и внешних зависимостей для самого скрипта нет.

<a id="english"></a>

<details>
<summary>English overview</summary>

An introductory exercise from the [Yandex Practicum](https://practicum.yandex.ru/) backend Python course, based on [yandex-praktikum/backend_test_homework](https://github.com/yandex-praktikum/backend_test_homework). The script prints a short message; the test checks the required files and imports the script successfully.

Run `python3 program.py`. Install pytest in a virtual environment and run `python -m pytest` for the automated check. This is a small learning exercise.

</details>

---

Автор: [Артём Леонов](https://github.com/artemleonich).

