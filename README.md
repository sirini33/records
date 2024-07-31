# records

# Hospital Management API

This is a RESTful API for managing patient records and doctor information in a hospital setting, built using Django and Django REST Framework. The API supports user authentication via JSON Web Tokens (JWT) and allows for CRUD operations on patients, doctors, and departments.

## Features

- User registration and authentication using JWT.
- User groups for Doctors and Patients.
- CRUD operations for:
  - Patients
  - Doctors
  - Departments
  - Patient Records
- Permissions to ensure that users can only access their own data.

## Technologies Used

- Django
- Django REST Framework
- SQLite
- Django Simple JWT for authentication

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/hospital-management-api.git
   cd hospital-management-api

**2. setup virtual environment:**
     python -m venv venv
     source ./venv/Scripts/activate
**3. Install the dependencies:**
    pip install -r requirements.txt
**4. Run migrations**
    python manage.py makemigrations
    python manage.py migrate
**5. Create Superuser**
    python manage.py runserver
 **6. Access the API**
     Open your browser and navigate to http://127.0.0.1:8000/api/ to access the API.

