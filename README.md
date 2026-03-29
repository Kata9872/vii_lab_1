<div align="center">
  <h1>iir-ai-labs-template</h1>
  <em>Шаблон для лабораторных работ по курсу «Введение в ИИ»</em>
  <br />
  <br />
  <p align="center">
    <a href="#"/>
      <img src="https://img.shields.io/badge/python-3.10-blue">
    </a>
    <a href="https://github.com/astral-sh/uv"/>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/uv/main/assets/badge/v0.json">
    </a>
    <a href="https://github.com/astral-sh/ruff"/>
      <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json">
    </a>
    <a href="https://github.com/pre-commit/pre-commit"/>
      <img src="https://img.shields.io/badge/pre--commit-enabled-blue?logo=pre-commit">
    </a>
    <a href="https://conventionalcommits.org"/>
      <img src="https://img.shields.io/badge/Conventional%20Commits-1.0.0-%23FE5196?logo=conventionalcommits&logoColor=white&color=blue">
    </a>
  </p>
</div>

## Задача

- Тип задачи:
- Датасет:
- Метрика качества:

Краткое описание задачи (1–3 предложений).

## Результаты

| Метрика | Train | Validation |
| ------- | ----- | ---------- |
|         |       |            |

## Подготовка датасета

Описание шагов, как скачать датасет и подготовить его для дальнейших обучения и валидации.

## Как воспроизвести

Команда обучения:

Команда валидации:

## Development

- Установите [uv](https://docs.astral.sh/uv/getting-started/installation/) и синхронизируйте зависимости:

```bash
uv sync --frozen
```

- Активация виртуального окружения:

```bash
source .venv/bin/activate
```

- Не забудьте использовать `pre-commit` хуки:

```bash
pre-commit install
```
