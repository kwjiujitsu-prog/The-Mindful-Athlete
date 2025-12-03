# Backend (Python)

This folder contains a minimal Flask backend skeleton.

Run locally (Windows PowerShell):

```powershell
cd backend
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
python app.py
```

Endpoints:
- `GET /` — basic message
- `GET /health` — health check
