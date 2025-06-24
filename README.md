# Django Dashboard using CanvasJS
This project implements an interactive web-based dashboard using Django (Python) for the backend and CanvasJS for dynamic chart rendering on the frontend. It allows users to visualize data through interactive charts directly within a Django-powered web application.

---

## Features

* Django-based web application
* Interactive charts using CanvasJS
* Modular app structure (charts app)
* Simple SQLite database backend

---

## Project Structure

```
├── charts/
│   ├── admin.py
│   ├── apps.py
│   ├── migrations/
│   ├── models.py
│   ├── static/
│   │   ├── canvasjs.min.js
│   │   ├── script.js
│   │   └── style.css
│   ├── templates/
│   │   └── index.html
│   ├── urls.py
│   └── views.py
├── dashboard/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── db.sqlite3
├── manage.py
└── Readme.md
```

---

## Setup Instructions

### 1. Clone the repository

```bash
git clone <repository-url>
cd Django-Dashboard-using-CanvasJS-Python-Charts
```

### 2. Create virtual environment (optional but recommended)

```bash
python -m venv venv
source venv/bin/activate  # (Linux/Mac)
venv\Scripts\activate  # (Windows)
```

### 3. Install dependencies

```bash
pip install django
```

### 4. Run migrations

```bash
python manage.py migrate
```

### 5. Run the server

```bash
python manage.py runserver
```

### 6. Open in browser

Visit: `http://127.0.0.1:8000/` to access the dashboard.

---

## Technology Stack

* Python
* Django Framework
* CanvasJS (for charts)
* SQLite (default Django DB)
* HTML/CSS/JavaScript

---

