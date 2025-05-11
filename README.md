# Remind-me-later

**Remind-me-later** is a minimalist Django-powered API that allows users to schedule reminders via **SMS** or **Email** for a specific **date** and **time**. It serves as the backend for a frontend UI built by JavaScript developers.

---

## Features

- Create reminders with:
  - Custom message
  - Specific date and time
  - Delivery method (SMS or Email)
- RESTful API endpoint (`POST /api/reminders/`)
- Built with Django and Django REST Framework

---

## Tech Stack

- **Python 3.10+**
- **Django 4.x**
- **Django REST Framework**
- **SQLite3** (default)

---

## API Usage

### Endpoint

```http
POST /api/reminders/
```

---

## Setup Locally

# 1. Clone the repository
https://github.com/Dipanshu682/remind_me_later.git

# 2. Create virtual environment
- python -m venv env
- .\venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run migrations
python manage.py migrate

# 5. Run server
python manage.py runserver
