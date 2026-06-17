# FastAPI Blog

A small FastAPI app with sample blog post data.

## Setup

```bash
uv sync
uv run uvicorn main:app --reload
```

Then open `http://127.0.0.1:8000`.

## Endpoints

- `/` and `/posts` return a simple HTML page.
- `/api/posts` returns the sample posts as JSON.
