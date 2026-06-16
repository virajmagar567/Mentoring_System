Mentoring System
A web-based Mentoring System built using Python (Django Framework) and HTML.
This system facilitates seamless interaction between students and mentors by allowing students to manage their academic and certification records, while enabling mentors to access this information.

Features
Student Functionality:

Upload personal details and certifications
View uploaded data
Delete details or certifications if needed
Mentor Functionality:

View student profiles and submitted certifications
Tech Stack
Backend: Python (Django Framework)
Frontend: HTML
Database: Default Django ORM (SQLite by default)
Setup Instructions
Prerequisites
Before setting up the project, make sure you have the following installed on your system:

Python (version 3.6 or above)
Download it through the Python Official Website or microsoft store

pip (Python package installer)
Usually comes bundled with Python. To check if it's installed:

pip --version
pip modules (Required Modules)

pip install django
pip install django_widget_tweaks
pip install pillow 

Quick Start
Click on Code (green button) and select Download ZIP
Extract the downloaded ZIP file to your desired location
Open the extracted folder (the one containing manage.py)
Right-click inside the folder and select Open Terminal or Open Command Prompt
Run the following command:
python manage.py runserver
Open your browser and go to http://127.0.0.1:8000/ to access the website
The Default Login for Admin is
Username
Admin
Password
Admin@123
Make Sure to change the admin password using the admin panel
To add a new admin open the command prompt and enter
python manage.py createsuperuser
