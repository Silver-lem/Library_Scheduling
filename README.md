# Library Scheduling – Django + React (Project)

This is a project built to understand how **Django**, **React**, and **MySQL** can work together in a single application.

The Initial Set-up of this project is:
- Backend–frontend integration
- Proper environment configuration
- Safe handling of credentials
- Basic project structure using modern tools

---

## Tech Stack

- **Backend:** Django (Python)
- **Frontend:** React
- **Database:** MySQL
- **Environment Management:** Pipenv
- **Version Control:** Git & GitHub

---

## Project Structure
Library_Scheduling/
├── Library/ # Django project (settings, urls, wsgi)
├── frontend/ # React application
├── manage.py
├── Pipfile
├── requirements.txt
└── README.md


---

## Backend Setup (Django)

- Django is configured to use **MySQL** instead of SQLite
- Database credentials are stored securely using a **`.env` file**
- No sensitive information is committed to the repository
- Default Django migrations (admin, auth, sessions) are applied

---

## Frontend Setup (React)

- React is set up as a separate frontend
- The frontend successfully renders and runs alongside Django
- This setup is used to learn Django–React integration

---

## Environment & Security

- Virtual environments are managed using **Pipenv**
- Sensitive files (`.env`, virtual environments, node_modules) are ignored using `.gitignore`
- No passwords, secrets, or credentials are hardcoded
---

## How to Run 

1. Set up a virtual environment using Pipenv
2. Configure database credentials in a `.env` file
3. Run Django backend using `python manage.py runserver`
4. Run React frontend using `npm start`

---


