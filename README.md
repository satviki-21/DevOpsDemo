# DevOps Demo Website

## Overview

This project is a Django-based web application developed to demonstrate DevOps concepts. It includes a simple multi-page website along with Git version control, GitHub integration, GitHub Actions for Continuous Integration (CI), automated testing, and Docker containerization.

## Features

- Home page
- About page
- Contact page
- Responsive Bootstrap interface
- Git version control
- GitHub repository integration
- GitHub Actions CI pipeline
- Docker support

## Technologies Used

- Python 3.9
- Django 4.2
- HTML
- Bootstrap 5
- Git
- GitHub
- GitHub Actions
- Docker

## Run Locally

```bash
pip install -r requirements.txt
python manage.py runserver
```

Open:

```
http://127.0.0.1:8000/
```

## Run with Docker

```bash
docker build -t devops-demo .
docker run -p 8000:8000 devops-demo
```

## Continuous Integration

The project uses GitHub Actions to:
- Install project dependencies
- Run Django tests automatically
- Verify that changes do not break the application

## Author

Satviki Atakani
