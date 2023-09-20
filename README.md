# Django CRUD App README

This is a simple CRUD (Create, Read, Update, Delete) application built using Django and Django Rest Framework. It provides API endpoints to manage user records with `name` and `user_id` fields.

## Getting Started

These instructions will help you set up and run the CRUD app on your local machine for development and testing purposes.

### Prerequisites

To run this app, you will need:

- Python 3.7 or higher
- Django 3.0 or higher
- Django Rest Framework

### Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/Mkothm/crud-api-endpoints
   cd crud-api-endpoints
   ```
### Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

### Install Project Dependencies
pip install -r requirements.txt

python manage.py migrate

python manage.py createsuperuser

### Run server
python manage.py runserver

### API Endpoints
```bash
List all users: GET /api/users/

Create a new user: POST /api/users/

Retrieve a user by ID: GET /api/users/<int:pk>/

Update a user by ID: PUT /api/users/<int:pk>/

Delete a user by ID: DELETE /api/users/<int:pk>/
```

