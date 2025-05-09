# Vehicle Registration System 🚗

This Django-based backend project simulates a vehicle registration system with features like email notifications and a basic map interface. It allows adding vehicles, tracking junction crossings, and notifying users by email.

---

## 📌 Features

- Vehicle registration and tracking
- Basic map integration (HTML/CSS mock-up)
- Email notifications when vehicles pass junctions
- Django backend logic (views, models, URLs)
- Admin access to manage vehicles and junctions

---

## 🛠️ Technologies Used

- Python 3.11
- Django 4.x
- SQLite3 (default database)
- Gmail SMTP (for sending email alerts)
- HTML/CSS for embedded map view

---

## 📁 Project Structure

```text
vehicle_registration/
├── vehicles/                # App logic (models, views)
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── admin.py
├── vehicle_project/         # Django project files
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── manage.py
├── requirements.txt
└── README.md
```

---

## 🚀 Installation & Running

### 1. Clone the repository

```bash
git clone https://github.com/AbdellahSbh/Portfolio_Vehicle_Registration_by_AbdellahSbh.git
cd Portfolio_Vehicle_Registration_by_AbdellahSbh
```

### 2. Create a virtual environment

```bash
# Windows
python -m venv env
env\Scripts\activate

# macOS/Linux
python3 -m venv env
source env/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 5. Run the development server

```bash
python manage.py runserver
```

---

## 💬 Email Notification Setup

- A Gmail account was created for testing.
- Enable **Less secure apps** in Gmail settings.
- Use an **App Password** or generated password in `settings.py`.

Example config:

```python
EMAIL_BACKEND = 'django.core.mail.backends.smtp.EmailBackend'
EMAIL_HOST = 'smtp.gmail.com'
EMAIL_PORT = 587
EMAIL_USE_TLS = True
EMAIL_HOST_USER = 'youremail@gmail.com'
EMAIL_HOST_PASSWORD = 'yourapppassword'
```

---

## 🗺️ Map Integration

- Basic HTML/CSS used to simulate a map view
- Map is not interactive but serves as a visual placeholder

---

## 📝 Notes

- This project is not meant for production use
- Email functionality is functional but not secure for real deployments
- Map is for demo only — not based on Google Maps API

---

## 📄 License

This project is developed for academic purposes as part of the Programming Clinic module  
at Lancaster University Leipzig – Michaelmas Term 2025.
