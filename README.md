<p align="center">
  <h1 align="center">Cloud Computing Monolith Architecture</h1>
</p>

<p align="center">
  <em>FastAPI monolith for fest registration, checkout, and load testing</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white" alt="SQLite" />
  <img src="https://img.shields.io/badge/Jinja2-B41717?style=flat&logo=jinja&logoColor=white" alt="Jinja2" />
  <img src="https://img.shields.io/badge/Locust-1C6EF2?style=flat&logo=locust&logoColor=white" alt="Locust" />
</p>

<br>

## ⚙️ Setup Instructions

1. Create a virtual environment (optional but recommended).

**Mac/Linux**

```
python3 -m venv .venv
source .venv/bin/activate
```

**Windows**

```
python -m venv .venv
.\.venv\Scripts\activate
```

2. Install dependencies:

```
pip install -r requirements.txt
```

3. Seed the database with events:

```
python insert_events.py
```

4. Run the server:

```
uvicorn main:app --reload
```

5. Open the app:

- http://127.0.0.1:8000/login
