# Vehicle Registration System

This is a Django-based backend project that simulates a vehicle registration system with basic CRUD operations and car movement simulation. It includes email notifications, emergency alerts, and Google Maps integration for visualizing traffic and vehicle flow.

---

## Features

- Register and manage vehicle data
- Handle vehicle movement simulation via coordinates
- Emergency vehicle notification system
- Email alerts for traffic violations
- Integration with Google Maps API (or mockup)
- JSON-based API responses
- Includes UML diagrams and presentation slides

---

## Technologies Used

- **Language:** Python 3.11
- **Framework:** Django
- **Frontend:** Google Maps integration (JavaScript or iframe)
- **Email System:** Django email backend (SMTP or console)
- **Database:** SQLite (default Django DB)
- **Others:** Requests, JSON, etc.

---

## Project Structure


. ├── registration/ # Handles emergency notification features │ ├── views.py │ ├── urls.py │ └── models.py │ ├── vehicleregistration/ # Main Django project configuration │ ├── settings.py │ ├── urls.py │ └── ... │ ├── Slides/ # Weekly project presentations ├── UMLs/ # Class, sequence, use case diagrams ├── db.sqlite3 # SQLite database ├── manage.py ├── README.md └── venv/ # Local virtual environment (not needed on GitHub)




> You can delete the `venv/` folder before pushing to GitHub to keep the repo clean.

---

## Installation and Running

1. **Clone the repository**

git clone https://github.com/AbdellahSbh/Portfolio_Vehicle_Registration_by_AbdellahSbh.git cd vehicle_registration_system


2. **Set up virtual environment**

python -m venv env env\Scripts\activate # Windows source env/bin/activate # macOS/Linux


3. **Run migrations and start the server**
   python manage.py migrate python manage.py runserver

   
4. **Access the system**

Open your browser at:  
`http://localhost:8000/`

---

## Notes

- Most routes are under the `registration/` app
- Google Maps features may require API key setup or work with demo data
- Email features can be tested using Django’s console backend in `settings.py`
- Simulation may involve JS or backend logic to animate car positions

---

## To-Do / Future Improvements

- Add vehicle update/delete routes with proper UI
- Improve simulation accuracy with real-time data
- Implement user authentication and role-based access (admin/driver)
- Replace in-memory or mock logic with full database tracking
- Add test cases and documentation

---

## License

This project was developed as part of Lancaster University Leipzig’s Programming Clinic module – Michaelmas Term 2025.


