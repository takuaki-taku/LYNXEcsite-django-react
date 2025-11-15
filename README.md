# LYNX E-commerce Site

A full-stack e-commerce website built with Django (backend) and React (frontend).

## Overview

This project is an e-commerce platform that combines Django's powerful backend capabilities with React's modern frontend framework.

## Tech Stack

- **Backend:**
  - Django
  - Python
  - SQLite/PostgreSQL

- **Frontend:**
  - React
  - Next.js
  - JavaScript/TypeScript

## Project Structure

- `ecsite_with_django/` - Django backend application
- `next.js-frontend/` - Next.js frontend application

## Setup

### Backend Setup

```bash
cd ecsite_with_django

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Create superuser
python manage.py createsuperuser

# Start the server
python manage.py runserver
```

### Frontend Setup

```bash
cd next.js-frontend

# Install dependencies
npm install

# Start the development server
npm run dev
```

## Features

- Product listing and search
- Shopping cart functionality
- User authentication
- Order management
- Admin panel

## License

MIT License
