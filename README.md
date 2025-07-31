Trip Booking System
A simple Trip Booking Web Application built using PHP, SQL, HTML, CSS to allow users to register, view trips, and make bookings.

-Features
User Registration and Login
Trip Booking functionality
Stores booking data in the database
Organized front-end with custom styles
PHP backend for handling form submissions and bookings
SQL database integration for storing user and booking information

-Technologies Used
Frontend: HTML, CSS (style.css, style2.css)
Backend: PHP
Database: MySQL (SQL scripts included)

-Project Structure
Trip-Booking/
│── img/                 # Images used in the project  
│── php/                 # PHP scripts (if separated)  
│── sql/                 # Database files or SQL dump  
│── style/               # Stylesheets  
│── booking_data/        # Stores booking-related data  
│── Home.php             # Homepage  
│── index.php            # Landing page / main entry  
│── process_booking.php  # Handles trip booking  
│── process_details.php  # Processes user details  
│── register.php         # Registration page  
│── store.php            # Stores booking info in DB  
│── Style.css            # Main stylesheet  
│── style2.css           # Additional stylesheet  


-Import the database:
Open phpMyAdmin (or MySQL CLI).
Create a database (e.g., trip_booking).
Import the SQL file from the sql/ folder.
Configure database connection:
Open the PHP files (process_booking.php, store.php, etc.).
Update database credentials (host, username, password, dbname).
