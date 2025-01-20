# 1. Project Structure
```text
procureezy_ai/
├── backend/
│   ├── main.py               # Entry Point (FastAPI application)
│   ├── db.py                 # Postgres Connection Settings
│   ├── models.py             # SQLAlchemy-models
│   ├── schemas.py            # Pydantic schemas 
│   └── services/
│       ├── llm_service.py      # LLM logic
│       ├── external_service.py # Fallback functions to the external API
│       └── search_service.py   # Search logic (by DB and fallback)
├── tests/
│   ├── test_search.py          # Example of unit tests
├── README.md
└── requirements.txt

```
---

## Install the dependencies:

```text
pip install -r requirements.txt
```
---
