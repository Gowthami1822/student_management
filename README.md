# student_management
# student_management
Student Management System

A web-based Student Management System built with Django, using MySQL as the database, Docker for containerization, and Pipenv for Python dependency management.
This project supports local development using virtual environments, as well as containerized deployment using Docker and Docker Compose.

Features

->Full HTML-based CRUD (Create, Read, Update, Delete) operations for Students
->Django Admin panel for easy data management
->MySQL database integration with persistent volume
->Dockerized services for easy setup and deployment
->Pipenv for clean and reproducible Python environment

Project Structure

student_management/
Dockerfile
docker-compose.yml
manage.py
Pipfile
Pipfile.lock
README.md
student_mgmt/ (Django project)
settings.py
urls.py
wsgi.py
students/ (App for student CRUD)
models.py
views.py
urls.py
templates/
Run with Docker (Recommended)

Build and Run Containers

->docker-compose up --build
->Access Application
    App: http://127.0.0.1:8000
  
