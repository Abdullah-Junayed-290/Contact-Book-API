# Contact-Book-API

This is a RESTful API built with Django REST Framework for managing a contact book.

## Features

- Create, read, update, and delete (CRUD) contacts
- Built using Django and Django REST Framework
- Designed as a backend API service

## Getting Started

### Prerequisites

- Python 3.8+
- Django
- Django REST Framework

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Abdullah-Junayed-290/Contact-Book-API.git
   cd Contact-Book-API
   ```

2. **Create and activate a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use venv\Scripts\activate
   ```

3. **Install dependencies**
   *(Add the actual package manager command here, e.g., `pip install -r requirements.txt` if you provide the file.)*

4. **Apply migrations**
   ```bash
   python manage.py migrate
   ```

5. **Run the development server**
   ```bash
   python manage.py runserver
   ```

## API Endpoints

| Method | Endpoint         | Description          |
|--------|------------------|---------------------|
| GET    | /contacts/       | List all contacts   |
| POST   | /contacts/       | Create a contact    |
| GET    | /contacts/{id}/  | Retrieve a contact  |
| PUT    | /contacts/{id}/  | Update a contact    |
| DELETE | /contacts/{id}/  | Delete a contact    |

*(Update the endpoints as per your actual implementation.)*

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project currently does not specify a license.

## Author

[Abdullah-Junayed-290](https://github.com/Abdullah-Junayed-290)
