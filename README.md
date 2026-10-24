# Full-Stack E-Commerce Store

A complete e-commerce web application built with a **Django** backend and a **React** frontend — product catalogue, cart and order flow, and a clean separation between API and UI.

## Tech Stack

- **Backend:** Python, Django (with a dedicated `store` app), environment-based configuration via `.env`
- **Frontend:** React, Vite, JavaScript
- **Database:** PostgreSQL

## Project Structure

```
├── backend/          # Django project (manage.py, store app, settings)
└── frontend/         # React + Vite single-page application
```

## Getting Started

### Backend

```bash
cd backend
python -m venv venv
source venv/bin/activate        # on Windows: venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

Create a `.env` file in `backend/` with your local settings (secret key, database credentials, debug flag) before running.

### Frontend

```bash
cd frontend
npm install
npm run dev
```

The frontend runs on Vite's dev server and talks to the Django API.

## Author

**Usman Ali Khan** — Full-Stack Developer, Lahore, Pakistan
Portfolio: [usmanali.site](https://usmanali.site)
