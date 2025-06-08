# Django Authentication

A basic Django project demonstrating user authentication features using JWT, including user registration, login, logout, change password, and forget password functionality.

## 🚀 Features

- User registration
- Login and logout functionality
- Change password
- Forget password (password reset)


## 📦 Project Structure

The project is organized as a standard Django application. Key components include:

- Django views and URLs for authentication endpoints
- JWT-based authentication for secure, stateless session management
- User models and serializers for handling user data


## 🛠️ Getting Started

Follow these steps to set up and run the project locally:

1. **Clone the repository:**

```bash
git clone https://github.com/alimurtzaa/django-authentication.git
cd authproject
```

2. **Create and activate a virtual environment:**

```bash
python -m venv venv
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate
```

3. **Install dependencies:**

```bash
pip install -r requirements.txt
```

4. **Apply database migrations:**

```bash
python manage.py migrate
```

5. **Create a superuser (optional, for admin access):**

```bash
python manage.py createsuperuser
```

6. **Run the development server:**

```bash
python manage.py runserver
```

7. **Access the app:**
    - Open your browser and go to `http://localhost:8000/`

## 🔑 Authentication Endpoints

The project exposes endpoints for:

- User registration
- User login (returns JWT)
- User logout (JWT blacklist/expiration)
- Change password
- Forgot password (send reset instructions)

Refer to the codebase for exact endpoint URLs and request/response formats.

**Note:** This project provides a basic foundation for JWT-based authentication in Django. For production use, ensure to update security settings and follow best practices for handling sensitive data.

