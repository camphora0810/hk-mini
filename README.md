# HK Mini API

FastAPI + Uvicorn minimal API. Endpoint: `/health` → `{"status":"ok"}`

## Quickstart (Windows cmd)
    python -m venv .venv
    .\.venv\Scripts\activate.bat
    pip install fastapi uvicorn[standard]
    uvicorn app.main:app --reload

## Project structure
    app/
      main.py
    .gitignore
    README.md



