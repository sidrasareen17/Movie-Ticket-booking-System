# Movie-Ticket-booking-System
# Movie Ticket Booking System (XAMPP)

This is a simple Movie Ticket Booking System built for XAMPP (PHP + MySQL).
Features:
- Register / Login
- Browse movies
- Book tickets (select seats and show time)
- Simulated payment (mock)
- Generate final ticket PDF containing user's name and booking details

**Setup**
1. Copy this project folder into your XAMPP `htdocs` directory (e.g. `C:/xampp/htdocs/movie_ticket_booking_xampp`).
2. Import the SQL file `movie_ticket_booking.sql` into phpMyAdmin or run it in MySQL to create the database and sample data.
3. Ensure PHP's `mysqli` extension is enabled (default in XAMPP).
4. Access the app at: `http://localhost/movie_ticket_booking_xampp/index.php`

**Default sample account**
- username: testuser
- email: test@example.com
- password: password123

If you want stronger password hashing, replace MD5 usage with password_hash in registration and password_verify in login.

