# -alx_travel_app_0x00

A Django-based web application for managing travel listings, bookings, and reviews. Built as part of the ALX Africa web development curriculum.

## Features

- **Listings:** Manage travel listings.
- **Bookings:** Book listings with ease.
- **Reviews:** Leave and view reviews.
- **API:** RESTful API endpoints with Django REST Framework.
- **Swagger UI:** Interactive API documentation.

## Tech Stack

- **Backend:** Python, Django, Django REST Framework
- **Database:** MySQL
- **API Docs:** Swagger (drf-yasg)
- **Environment:** `.env` file for configuration

## Installation

```bash
# Clone repo
git clone https://github.com/Audrey-Okumu/-alx_travel_app_0x00.git
cd alx_travel_app_0x00
```
# Create virtual environment
```
python -m venv venv
```
# Activate
```
venv\Scripts\activate   # Windows
source venv/bin/activate  # macOS/Linux
```

# Install dependencies
```
pip install -r requirements.txt
```

# Configure .env

# Apply migrations
```
python manage.py makemigrations
python manage.py migrate
```

# Run server
```
python manage.py runserver
```
