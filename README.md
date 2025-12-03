# Mindful Athlete (monorepo)

This repository contains two Expo-managed React Native apps and a minimal Python backend.

Structure
- `frontend/` — primary Expo + TypeScript app
- `mobile-app/` — secondary Expo + TypeScript app
- `backend/` — Python (Flask) skeleton

Quick start

- Frontend
```powershell
cd frontend
npm install
npx tsc --noEmit
npm run start
```

- Mobile app
```powershell
cd mobile-app
npm install
npx tsc --noEmit
npm run start
```

- Backend
```powershell
cd backend
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
python app.py
```

Notes
- `./.github/copilot-instructions.md` contains guidance for AI agents and maintainer notes.
- A GitHub Actions workflow is present at `./.github/workflows/ci.yml` to run TypeScript checks.
