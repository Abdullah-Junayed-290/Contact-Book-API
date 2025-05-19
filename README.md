📇 Contact Book API

A RESTful API built with Django and Django REST Framework to manage personal contacts. This API allows users to create, retrieve, update, and delete contact information efficiently.

🚀 Features

CRUD Operations: Create, Read, Update, and Delete contacts.

RESTful Endpoints: Follows REST principles for API design.

SQLite Database: Lightweight and easy-to-use database for development.

Modular Structure: Organized codebase for scalability and maintenance.


🛠️ Technologies Used

Backend Framework: Django

API Framework: Django REST Framework

Database: SQLite (default for Django projects)


📂 Project Structure

Contact-Book-API/
├── api/
│   ├── migrations/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── serializers.py
│   ├── tests.py
│   └── views.py
├── contact_book/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── db.sqlite3
└── manage.py

⚙️ Installation & Setup

1. Clone the Repository:

git clone https://github.com/Abdullah-Junayed-290/Contact-Book-API.git
cd Contact-Book-API


2. Create a Virtual Environment:

python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate


3. Install Dependencies:

pip install -r requirements.txt


4. Apply Migrations:

python manage.py migrate


5. Run the Development Server:

python manage.py runserver

The API will be accessible at http://127.0.0.1:8000/.



📬 API Endpoints

Method	Endpoint	Description

GET	/api/contacts/	Retrieve all contacts
POST	/api/contacts/	Create a new contact
GET	/api/contacts/{id}/	Retrieve a specific contact
PUT	/api/contacts/{id}/	Update a specific contact
DELETE	/api/contacts/{id}/	Delete a specific contact


> Replace {id} with the contact's unique identifier.



🧪 Running Tests

To run the test suite:

python manage.py test

📝 License

This project is licensed under the MIT License.

🙋‍♂️ Author

Md. Abdullah Junayed
GitHub Profile


