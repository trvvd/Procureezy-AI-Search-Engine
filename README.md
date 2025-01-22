# 1. Project Structure
```text
procureezy_ai/
├── database_setup.py         # (SQL-code)
├── main.py                   # (FastAPI-application)
├── schemas.py                # (Pydantic-schemes)
├── search_service.py         # (Logic of search + fallback)
├── llm_service.py            # (LLM)
├── agent_workflow.py         # (Future implementation of "agents" / chain-of-thought)
├── requirements.txt          # (Dependencies)
├── .env                      # (Environment variables: DATABASE_URL, etc.)
└── README.md                 # (Documentation)

```
---

## Install the dependencies:

```text
pip install -r requirements.txt
```
---
