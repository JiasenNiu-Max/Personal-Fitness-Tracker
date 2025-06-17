# Personal Fitness Tracker

## 📌 Project Overview

This web application allows users to register, log in, record their workouts, view workout tutorials, and manage their personal fitness data. Built using Python Flask, the system includes a secure login system, personalized dashboards, and a well-structured database to store user profiles and exercise logs.

## 🔧 Technologies Used

- 🐍 Python 3 + Flask
- 🗃 SQLite (via SQLAlchemy ORM)
- 🧑 HTML/CSS/JavaScript for front-end
- 🔐 Login/Signup system
- 📁 Flask templates and static file serving

## 🗂️ Project Structure

```

CITS5505-Group10-Project-main/
├── app.py                      # Main application entry point
├── auth.py                    # Authentication handling (login, logout)
├── record.py                  # Workout recording logic
├── user\_profile.py            # User profile view/edit logic
├── models.py                  # SQLAlchemy database models
├── init\_db.py                 # Database initialization
├── login\_system/              # HTML + CSS for login system
│   ├── login.html
│   ├── signup.html
│   ├── forgot\_password.html
│   └── style.css
├── templates/                 # HTML templates (if applicable)
├── static/                    # Static resources (JS, images, etc.)
├── migrations/                # DB migration scripts
├── requirements.txt           # Python dependencies
├── instance/secret\_key.txt    # Flask secret key (for session encryption)
└── \*.html / \*.css / \*.js      # Other UI files

````

## 🚀 Features

- User authentication (Signup, Login, Password Reset)
- Edit and view personal information
- Add and view workout records
- Workout tutorial image integration
- Persistent database (SQLite)
- Custom styling and user interface
- Database migration and seed scripts included

## ▶️ Getting Started

### 1. Install Dependencies

```bash
pip install -r requirements.txt
````

### 2. Initialize the Database

```bash
python init_db.py
```

### 3. Run the Application

```bash
python app.py
```

The app will be available at: `http://127.0.0.1:5000`

## 📸 Screenshots

* `log_workouts.png` – Workout logging interface
* `workout_tutorials.png` – Tutorial preview
* `profile_pic.jpg` – Sample user image

## 📂 Database Migrations

Included:

* `migrations/initial_migration.py`
* `migrations/insert_user.py`
* Excel files with exported user and workout data

## 🔒 Security Note

* Do not expose `instance/secret_key.txt` in production
* Consider using Flask-WTF and CSRF protection in future development

## 🧑‍💻 Contributors

Group 10 – CITS5505 Web Technologies
(Names can be added here)

## 📄 License

This project is intended for educational use only.



