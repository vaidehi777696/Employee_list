# Employee Management CRUD App

This is a simple Django-based CRUD (Create, Read, Update, Delete) application to manage employee records.

## Features

- List all employees
- Add a new employee
- Update existing employee details
- Delete an employee

## Tech Stack

- **Backend**: Python, Django
- **Database**: SQLite (default)
- **Frontend**: HTML (Django templates)

## Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/your-username/employee-management.git
cd employee-management
2. Create and activate a virtual environment

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
3. Install dependencies

pip install -r requirements.txt
If you don’t have a requirements.txt, you can create one with:


pip freeze > requirements.txt
4. Run migrations

python manage.py makemigrations
python manage.py migrate
5. Start the development server

python manage.py runserver
Visit http://127.0.0.1:8000/employee_list/ in your browser.
