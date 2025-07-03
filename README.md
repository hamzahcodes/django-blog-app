# 📝 Django Blog Application

A simple and customizable blog application built with Django. It allows users to create, read, update, and delete blog posts, with user authentication and a clean UI.

## 🚀 Features

- User registration and login/logout
- Create, update, and delete blog posts
- Rich text editor for post content
- Post listing with pagination
- Comments system (optional)
- Admin panel for managing content
- SEO-friendly URLs

## 📸 Screenshots

*Add screenshots of your app here if available.*

## 🛠️ Tech Stack

- **Backend:** Django (Python)
- **Frontend:** HTML5, CSS3, Bootstrap (or Tailwind, if you're using that)
- **Database:** SQLite (default) or PostgreSQL/MySQL
- **Version Control:** Git & GitHub

## 📦 Installation

1. **Clone the repository:**

```bash
git clone https://github.com/hamzahcodes/django-blog-app.git
cd my-project
```

2. **Create a virtual environment:**
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

3. **Install dependencies:**
```bash
pip install -r requirements.txt
```

4. **Run Migrations:**
```bash
py manage.py migrate
```

5. **Create super user for admin access:**
```bash
py manage.py createsuperuser
```

6. **Start the server:**
```bash
py manage.py runserver
```