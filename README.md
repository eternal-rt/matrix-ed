# MATRIX ED
Emergency department platform, real-time ED workflows &amp; tracking.


This is MATRIX ED – a system built specifically for emergency departments.

It's meant to handle the fast-moving stuff in the ED better than the usual big systems: real-time patient board, quick badge login, triage entry, placing orders, charting, bed tracking, and discharge basics.

Right now it's just me working on it

### What it has so far (or will have soon)

- Login screen with the starry background and badge tap/ID entry
- Live patient tracking board (status, room, timers, alerts)
- Triage form (chief complaint, vitals, ESI)
- Basic charting for nurses and docs
- Order entry (labs, imaging, meds)
- Simple bed/floor view
- Discharge notes and instructions

### Spec

- Backend: Python / FastAPI
- Frontend: React + Tailwind
- Database: PostgreSQL
- Auth: Keycloak (for badge and regular login)
- Real-time: WebSockets

### Setup (once you have access)

1. Clone the repo
2. docker compose up -d   (starts postgres + keycloak)
3. Backend: cd backend && uvicorn main:app --reload
4. Frontend: cd frontend && npm install && npm run dev

No real patient data will ever go in here during development. !!!!

If you're looking at this repo, you're probably helping or testing – reach out if you need anything.
