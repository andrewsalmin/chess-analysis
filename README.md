# ♟️ Анализ шахматных партий

[![Python](https://img.shields.io/badge/Python-3.11+-blue?logo=python)](https://www.python.org/)

[![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange?logo=jupyter)](https://jupyter.org/)

## 📘 О репозитории

Данный репозиторий содержит проект по анализу партий, сыгранных на lichess.org, выгружаемых с помощью Lichess API.

## 🌐 Онлайн‑просмотр

[![View in nbviewer](https://img.shields.io/badge/Open%20in-nbviewer-blue?logo=jupyter)](https://nbviewer.org/github/andrewsalmin/chess-analysis/blob/main/chess-analysis.ipynb)

[![Launch Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/andrewsalmin/chess-analysis/HEAD?labpath=chess-analysis.ipynb)

## 📁 Структура проекта

```bash
    .
    |
    ├── chess-analysis.ipynb
    ├── requirements.txt
    └── README.md
```

## ⚙️ Как запустить локально

```bash
    # Клонировать репозиторий:
    git clone https://github.com/andrewsalmin/chess-analysis.git

    # Перейти в папку проекта:
    cd chess-analysis

    # Создать виртуальное окружение (один раз):
    python -m venv venv

    # Активировать окружение:
    # Linux / macOS:
    source venv/bin/activate
    # Windows (PowerShell / CMD):
    venv\Scripts\activate

    # Установить зависимости в это окружение (один раз):
    pip install -r requirements.txt

    # Запустить ноутбук:
    jupyter notebook chess-analysis.ipynb
```

## 📜 Лицензия

Этот проект распространяется по лицензии [MIT](https://opensource.org/licenses/MIT).
