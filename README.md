# College Management System

A Django-based web application for managing college operations, including students, staff, attendance, and notifications.

## Setup Instructions

1. Clone the repository
2. Create a virtual environment and activate it
3. Install dependencies: `pip install -r requirements.txt`
4. Copy `.env.example` to `.env` and fill in your secrets
5. Run migrations: `python manage.py migrate`
6. Create a superuser: `python manage.py createsuperuser`
7. Start the server: `python manage.py runserver`

## Environment Variables
See `.env.example` for required variables.

## Features
- Student, staff, and admin management
- Attendance tracking
- Notifications
- Secure authentication

## License
MIT
