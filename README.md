# README.md
# Contacts Web Application

## Setup Instructions

1. Clone the repository:
   ```sh
   git clone <repo-link>
   cd contacts-web-app
   ```
2. Create and activate a virtual environment:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Apply migrations:
   ```sh
   python manage.py migrate
   ```
5. Run the server:
   ```sh
   python manage.py runserver
   ```
6. Access the API at `http://127.0.0.1:8000/contacts/`
7. Open the front-end page at `http://127.0.0.1:8000/`

