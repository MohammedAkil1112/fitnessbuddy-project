# FitBuddy — AI Fitness Plan Generator

A FastAPI + Jinja2 + SQLite application that generates personalized 7-day workout plans, nutrition/recovery tips, and feedback-based plan revisions using Google Gemini.

## Features

- Responsive Jinja2 web UI
- Personalized 7-day workout plan
- Nutrition/recovery tip
- Feedback-based plan update
- SQLite persistence
- REST API endpoints
- Admin dashboard
- Gemini AI integration
- Local fallback when no API key is configured

## Windows setup

```powershell
py -3.11 -m venv .venv

.\\.venv\\Scripts\\Activate.ps1

python -m pip install --upgrade pip

pip install -r requirements.txt

Copy-Item .env.example .env
