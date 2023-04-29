BloodConnect - Blood Management System

BloodConnect is a web-based blood management system built using Python 3 and Django framework. This system is designed to help blood banks, hospitals, and other healthcare organizations manage their blood inventories, donor information, and blood requests.

Admin Login Credential
Username:Paulabraham
Password:Paul@1998

Patient Login Credential

Username : ram
Password : 1234

DonorLogin Credential

Username: siva
Password: 1234

Features
BloodConnect includes the following features:

Donor registration and management
Blood request management
Blood inventory management
Blood donation history
Automatic email notifications to donors and blood banks
Donor search based on various criteria
User authentication and access control

Requirements

Python 3
Django 3.1
Django crispy forms
Django-filter
Pillow

Navigate into the project directory
cd bloodconnect

Install the required packages
pip install -r requirements.txt

Create a new database and update the database settings in settings.py.
Run the database migrations
python manage.py migrate

Create a superuser account
python manage.py createsuperuser

Run the development server.
python manage.py runserver
Navigate to http://127.0.0.1:8000 in your web browser to access the application.
