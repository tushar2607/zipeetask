#  Task Manager API (Django REST Framework)

A RESTful Task Manager API built with Django and DRF. It supports task CRUD operations, JWT-based authentication, role-based access (Admin/User), pagination, filtering, and Swagger documentation.

---

## Features

- User Registration & Login
- JWT Authentication (Simple JWT)
- CRUD for Tasks
- Role-based Access (Admin vs Regular User)
- Pagination & Filtering
- Swagger API Documentation
- Unit Tests

---

##  Tech Stack

- Django
- Django REST Framework
- djangorestframework-simplejwt
- django-filter
- drf-yasg (Swagger)

---

##  Project Structure
# 1. Clone the project
git clone <repo_url>
cd taskmanager

# 2. Create and activate a virtual environment
python -m venv venv
source venv/bin/activate  # or venv\\Scripts\\activate on Windows

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run migrations
python manage.py migrate

# 5. Create superuser (optional)
python manage.py createsuperuser

# 6. Start the server
python manage.py runserver

