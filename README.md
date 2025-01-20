## 1. Project Structure
```text
procureezy_ai/
├── backend/
│   ├── main.py               # Точка входа (FastAPI-приложение)
│   ├── db.py                 # Настройки подключения к Postgres
│   ├── models.py             # SQLAlchemy-модели
│   ├── schemas.py            # Pydantic-схемы (если нужно валидировать входные данные)
│   └── services/
│       ├── llm_service.py      # Логика LLM (пример – OpenAI)
│       ├── external_service.py # Функции fallback к внешнему API
│       └── search_service.py   # Поисковая логика (по БД и fallback)
├── tests/
│   ├── test_search.py          # Пример юнит-тестов
├── README.md
└── requirements.txt

```
---
