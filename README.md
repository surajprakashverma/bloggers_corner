# 📝 Blog Corner

Blog Corner is a Django-based blogging platform designed for simplicity, creativity, and seamless content management. The application allows users to create, publish, and manage blog posts with image support through an intuitive interface.

🌐 **Live Demo:**  
https://s-p-verma-blogs.onrender.com/

---

## 🚀 Features

- Create and manage blog posts
- Image upload support using Pillow
- Clean and responsive user interface
- Dynamic blog listing and detail pages
- Django Admin integration
- SQLite database support
- Static file management using WhiteNoise
- Render deployment ready

---

## 🛠️ Tech Stack

### Backend
- Python
- Django 5.2.7

### Frontend
- HTML
- CSS
- Bootstrap

### Database
- SQLite3

### Libraries
- Pillow
- WhiteNoise
- Gunicorn

### Deployment
- Render

---

## 📁 Project Structure

```text
Blog-Corner/
│
├── blog/
│   ├── migrations/
│   ├── admin.py
│   ├── models.py
│   ├── views.py
│   └── urls.py
│
├── bloggers_corner/
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   └── asgi.py
│
├── templates/
│   └── blog templates
│
├── static/
│   └── CSS, JS, Images
│
├── uploads/
│   └── Uploaded Blog Images
│
├── .idea/
│
├── manage.py
├── db.sqlite3
├── requirements.txt
├── Procfile
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/surajprakashverma/Blog-Corner.git
cd Blog-Corner
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Linux / macOS

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Database Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### Start Development Server

```bash
python manage.py runserver
```

Open:

```text
http://127.0.0.1:8000/
```

---

## 📸 Main Functionalities

- Publish blog articles
- Upload featured images
- Read blogs in a structured format
- Manage content through Django Admin
- Dynamic page rendering with Django Templates

---

## ☁️ Deployment on Render

### Build Command

```bash
pip install -r requirements.txt
```

### Start Command

```bash
gunicorn bloggers_corner.wsgi:application
```

### Environment Variables

```text
DEBUG=False
SECRET_KEY=your-secret-key
ALLOWED_HOSTS=your-render-domain.onrender.com
```

---

## 🎯 Learning Outcomes

This project demonstrates:

- Django Project Architecture
- Models and Database Operations
- URL Routing
- Template Rendering
- Static and Media File Handling
- Django Admin Customization
- Render Deployment
- WhiteNoise Integration

---

## 🌐 Live Application

🔗 Visit Blog Corner:

https://s-p-verma-blogs.onrender.com/

---

## 👨‍💻 Author

**Suraj Prakash Verma**

Software Engineer passionate about Django, Enterprise Integrations, Machine Learning, and Full-Stack Development.

GitHub: https://github.com/surajprakashverma
