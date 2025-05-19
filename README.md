# ðŸ“‡ Contact Book API

A RESTful API built with Django and Django REST Framework to manage personal contacts. This API allows users to create, retrieve, update, and delete contact information efficiently.

## ðŸš€ Features

- **CRUD Operations**: Create, Read, Update, and Delete contacts.
- **RESTful Endpoints**: Follows REST principles for API design.
- **SQLite Database**: Lightweight and easy-to-use database for development.
- **Modular Structure**: Organized codebase for scalability and maintenance.

## ðŸ› ï¸ Technologies Used

- **Backend Framework**: [Django](https://www.djangoproject.com/)
- **API Framework**: [Django REST Framework](https://www.django-rest-framework.org/)
- **Database**: SQLite (default for Django projects)

## ðŸ“‚ Project Structure

```
Contact-Book-API/
â”œâ”€â”€ api/
â”‚   â”œâ”€â”€ migrations/
â”‚   â”œâ”€â”€ __init__.py
â”‚   â”œâ”€â”€ admin.py
â”‚   â”œâ”€â”€ apps.py
â”‚   â”œâ”€â”€ models.py
â”‚   â”œâ”€â”€ serializers.py
â”‚   â”œâ”€â”€ tests.py
â”‚   â””â”€â”€ views.py
â”œâ”€â”€ contact_book/
â”‚   â”œâ”€â”€ __init__.py
â”‚   â”œâ”€â”€ asgi.py
â”‚   â”œâ”€â”€ settings.py
â”‚   â”œâ”€â”€ urls.py
â”‚   â””â”€â”€ wsgi.py
â”œâ”€â”€ db.sqlite3
â””â”€â”€ manage.py
```

## âš™ï¸ Installation & Setup

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/Abdullah-Junayed-290/Contact-Book-API.git
   cd Contact-Book-API
   ```

2. **Create a Virtual Environment**:

   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

3. **Install Dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

4. **Apply Migrations**:

   ```bash
   python manage.py migrate
   ```

5. **Run the Development Server**:

   ```bash
   python manage.py runserver
   ```

   The API will be accessible at `http://127.0.0.1:8000/`.

## ðŸ“¬ API Endpoints

| Method | Endpoint             | Description               |
|--------|----------------------|---------------------------|
| GET    | `/api/contacts/`     | Retrieve all contacts     |
| POST   | `/api/contacts/`     | Create a new contact      |
| GET    | `/api/contacts/{id}/`| Retrieve a specific contact |
| PUT    | `/api/contacts/{id}/`| Update a specific contact |
| DELETE | `/api/contacts/{id}/`| Delete a specific contact |

> Replace `{id}` with the contact's unique identifier.

## ðŸ§ª Running Tests

To run the test suite:

```bash
python manage.py test
```

## ðŸ“ License

This project is licensed under the [MIT License](LICENSE).

## ðŸ™‹â€â™‚ï¸ Author

- **Md. Abdullah Junayed**  
  [GitHub Profile](https://github.com/Abdullah-Junayed-290)
