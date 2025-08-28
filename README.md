\# HK Mini API

FastAPI + Uvicorn minimal API. Endpoint: `/health` → `{"status":"ok"}`



\## Quickstart

python -m venv .venv

..venv\\Scripts\\activate.bat

pip install fastapi uvicorn\[standard]

uvicorn app.main:app --reload

