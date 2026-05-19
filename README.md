Vedakshetra – Healthcare Service Management System

Vedakshetra is a web-based Healthcare Service Management System developed using **Python Django** framework. The system provides an online platform where users can explore hospitals, view healthcare packages, make bookings, complete payments, and provide feedback. Hospitals can manage services and packages, while administrators monitor and control the entire system.

The project aims to simplify healthcare service access by connecting **Admins**, **Hospitals**, and **Users** through a centralized platform.

---

 Features

👨‍💼 Admin Module
- Admin login
- District management
- Location management
- Hospital verification
- User management
- Package report generation
- Booking report
- Payment report
- Feedback report
- Overall summary dashboard
- Date-wise reports
- Chart-based analytics dashboard

🏥 Hospital Module
- Hospital registration
- Hospital login
- Add healthcare packages
- Add services
- Manage package services
- View bookings
- Confirm / Reject bookings
- View payments
- View user feedback

👤 User Module
- User registration
- User login
- Browse hospitals
- View available packages
- View services
- Book healthcare packages
- Payment processing
- Submit feedback and ratings
- View booking status

---

Technologies Used

Frontend
- HTML5
- CSS3
- Bootstrap
- JavaScript
- Chart.js

Backend
- Python
- Django Framework

Database
- SQLite

Tools
- VS Code
- Git
- GitHub

---

 🗂 Project Modules
1. Guest Module
Handles:
- User registration
- Hospital registration
- Login system

2. Admin Module
Handles:
- District and location management
- Hospital verification
- Reports and dashboard
- Monitoring system activities

3. Hospital Module
Handles:
- Package creation
- Service management
- Booking handling
- Payment monitoring

4. User Module
Handles:
- Package booking
- Payments
- Feedback submission

---

Reports Included

- District Report
- Location Report
- Hospital Registration Report
- Package Report
- Booking Report
- Payment Report
- Feedback Report
- Date Wise Payment Report
- Overall Summary Report
- Dashboard Analytics

---

Database Tables

Guest App
- User Register
- Hospital Register

Hospital App
- Packages
- Services
- Booking

User App
- Payments
- Feedbacks

Admin App
- District
- Location

---
Installation

Clone Repository

```bash
git clone https://github.com/aswathy2004/vedakshetra.git


Move into project folder:

cd vedakshetra

Create virtual environment:

python -m venv venv

Activate environment:

Windows:

venv\Scripts\activate

Install dependencies:

pip install -r requirements.txt

Run migrations:

python manage.py makemigrations
python manage.py migrate

Run server:

python manage.py runserver

Open browser:

http://127.0.0.1:8000
📸 System Workflow
Admin

Login → Add District → Add Location → Verify Hospitals → Generate Reports → Monitor Dashboard

Hospital

Register → Login → Add Package → Add Service → Manage Bookings → View Payments → View Feedback

User

Register → Login → Search Hospital → View Package → Book Package → Payment → Feedback

🎯 Objectives
Provide online healthcare package booking
Improve hospital service management
Reduce manual work
Enable centralized monitoring
Improve transparency between hospitals and users

🔮 Future Enhancements
Online appointment scheduling
AI healthcare recommendations
SMS / Email notifications
Payment gateway integration
Mobile application support
Medical history management
Real-time analytics dashboard

👨‍🎓 Academic Information

Project Title: Vedakshetra – Healthcare Service Management System

Developed For: Final Year Project

Course: BCA 

Framework: Django

📄 License

This project is developed for educational and academic purposes.

⭐ If you like this project, give it a star on GitHub!
