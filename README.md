# Overview

As a software engineer in training, I created this personal portfolio web application to deepen my understanding of Django and backend development. This project focuses on learning how to manage data models, templates, and views to dynamically generate content on a website.

The web app is a simple portfolio site built with Django. It allows users to view a list of projects and their descriptions. To run the app locally, activate your virtual environment and use the following command:

python manage.py runserver

Then open your browser and go to:
http://127.0.0.1:8000

My purpose for building this app was to explore how Django handles backend logic, URL routing, models, and template rendering. I wanted to practice deploying a working web app structure while gaining hands-on experience with dynamic content and MVC design.

[Software Demo Video](https://screenrec.com/share/RnBfhcFKYl)

# Web Pages

Home Page (/): Displays a list of portfolio projects. Each project is rendered dynamically from a Django model.

Admin Panel (/admin): Built-in Django admin interface where you can manage (add/edit/delete) project data.

In the future, individual project detail pages may be added.

The home page dynamically generates content using data stored in the Project model. Projects are listed using a loop in the Django template, pulling information from the database.

# Development Environment

Visual Studio Code

Python 3.12

Django 5.2.4

Windows PowerShell (for terminal commands)

Virtual environment for project isolation

# Useful Websites

{Make a list of websites that you found helpful in this project}
* [Django Documentation](https://docs.djangoproject.com/en/stable/)
* [Real Python Django Tutorial](https://realpython.com/get-started-with-django-1/)
* [Stack Overflow](https://stackoverflow.com/)
* [W3Schools Django Guide](https://www.w3schools.com/django/)

# Future Work

* Fix the issue preventing the site from loading correctly
* Add detail pages for individual projects
* Improve page styling and layout with CSS or Tailwind
* Add a contact form or resume download feature
