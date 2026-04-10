# REST_API_USING-Django

---RestApp – Django REST API---

This project is a REST API built using Django and Django REST Framework. I developed this project in Visual Studio Code to understand how backend APIs work and how to handle CRUD operations in Django.

About the Project:

RestApp is a simple API application where users can create, view, update, and delete data through API endpoints. This project helped me learn how to structure a Django project and work with REST APIs.

Features:
Perform CRUD operations (Create, Read, Update, Delete)
API development using Django REST Framework
Basic authentication and permissions
Organized project structure
Technologies Used
Python
Django
Django REST Framework
SQLite


Visual Studio Code
Project Structure:

restapp/models.py – defines database models

restapp/views.py – contains API logic

restapp/serializers.py – handles data conversion (JSON)

restapp/urls.py – API routing

How to Run the Project

Open the project in Visual Studio Code

Open terminal in VS Code


Create virtual environment:

python -m venv venv

Activate environment:

venv\Scripts\activate

Install dependencies:

pip install -r requirements.txt

Apply migrations:

python manage.py migrate

Run the server:

python manage.py runserver


API Endpoints

GET /api/ → get all data

POST /api/ → create new data

GET /api/<id>/ → retrieve single record

PUT /api/<id>/ → update record

DELETE /api/<id>/ → delete record


Testing:

I tested the API using browser and tools like Postman to check all endpoints and responses.


What I Learned:

How to build REST APIs using Django
How serializers work in Django REST Framework
Handling requests and responses
Structuring a backend project properly


Conclusion

This project gave me a clear understanding of how APIs are developed and how Django can be used for backend development.
