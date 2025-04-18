# Paw Rescue

A Django web application for animal rescue and adoption management. This platform helps connect animals in need with potential adopters and manages the adoption process.

## Features

- User Authentication (Login/Signup)
- Admin Panel for Rescue Management
- Animal Adoption Listings
- Volunteer Management
- Report Strays/Animals in Need
- Food and Health Information
- Donation System
- Location Services

## Tech Stack

- Python 3.11
- Django 5.1.6
- SQLite (Development) / PostgreSQL (Production)
- HTML/CSS
- Bootstrap
- Whitenoise for Static Files

## Local Development

1. Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/paw_rescue.git
cd paw_rescue
```

2. Install dependencies
```bash
pip install -r requirements.txt
```

3. Set up environment variables
Create a `.env` file in the root directory and add:
```
DJANGO_SECRET_KEY=your_secret_key
DJANGO_DEBUG=True
ALLOWED_HOSTS=localhost,127.0.0.1
```

4. Run migrations
```bash
python manage.py migrate
```

5. Create a superuser
```bash
python manage.py createsuperuser
```

6. Run the development server
```bash
python manage.py runserver
```

Visit http://127.0.0.1:8000/ to see the application running.

## Deployment

This application is configured for deployment on Render.com. See the `build.sh` script for deployment configuration. 