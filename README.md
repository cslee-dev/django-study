# Study Django Project

[![Python Version](https://img.shields.io/badge/python-3.11.9-blue.svg)](https://www.python.org/downloads/release/python-3119/)
[![Django Version](https://img.shields.io/badge/django-5.0.6-brightgreen.svg)](https://docs.djangoproject.com/en/5.0/releases/5.0.6/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)](https://travis-ci.org/)
[![Coverage Status](https://img.shields.io/badge/coverage-100%25-brightgreen.svg)](https://coveralls.io/)

## Introduction

This project, "Study Django", is created to help you get started with Django 5.0.6 using Python 3.11.9. It's a basic Django setup intended for educational purposes and further development.

## Requirements

- Python 3.11.9
- Django 5.0.6

## Installation

Follow these steps to set up the project on your local machine.

### 1. Clone the repository

```sh
git clone https://github.com/yourusername/study-django.git
cd study-django
```

### 2. Set up a virtual environment using pyenv and install dependencies
```sh
# Ensure you have pyenv installed
curl https://pyenv.run | bash

# Add pyenv to bash so that it loads every time you open a terminal
export PATH="$HOME/.pyenv/bin:$PATH"
eval "$(pyenv init --path)"
eval "$(pyenv init -)"
eval "$(pyenv virtualenv-init -)"

# Install Python 3.11.9 and create a virtual environment
pyenv install 3.11.9
pyenv virtualenv 3.11.9 study-django-env
pyenv activate study-django-env

# Install Django 5.0.6
pip install Django==5.0.6
```

### 3. Set up the Django project
```sh
# Navigate to the project directory
cd study_django

# Apply migrations
python manage.py migrate

# Run the development server
python manage.py runserver
```

### 4. Access the project
Open your web browser and go to http://127.0.0.1:8000/ to see the Django welcome page.