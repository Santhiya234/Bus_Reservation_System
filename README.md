# Bus_Reservation_System
This is a simple Bus Reservation System designed to facilitate the booking of bus tickets for passengers. It provides functionality for both customers to book tickets and administrators to manage bus routes, schedules, and bookings.

## Features

- *Customer Features:*
  - Search for available buses based on source and destination.
  - View bus schedules and available seats.
  - Book tickets for desired routes.
  - View booking history.

- *Administrator Features:*
  - Add, edit, or delete bus routes.
  - Manage bus schedules including departure times and seat availability.
  - View and manage bookings.
  - View sales reports and revenue.
## Technologies Used

- *Backend:* Python with Flask framework
- *Database:* SQLite
- *Frontend:* HTML, CSS, JavaScript
- *Additional Tools:* SQLAlchemy for ORM, Jinja2 for templating

## Folder Structure:
*app:* Contains the Flask application code.
*templates:* HTML templates for frontend.
*static:* Contains static files such as CSS and JavaScript.
## Conclusion:

Thank you for choosing our Bus Reservation System! We hope this system enhances your bus booking experience, whether you're a passenger looking for convenient travel options or an administrator managing bus operations efficiently.

PROJECT CREATED BY : 
LOGIN DETAILS:
UNAME: admin
Password:admin

#Project Running steps:
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
