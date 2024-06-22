# Hotel-Management-Project-Django
https://github.com/hkharsharaju/Hotel-Management-Project-Django/assets/138602401/e59233ff-b870-45e3-8909-2576a4e435c7
Hotel Reservation Management is a Django-based web application designed to streamline the process of booking hotel rooms. The application includes user authentication, admin verification, and a secure booking system to ensure a seamless experience for both users and administrators.

## Features

- **User Authentication**: Users must log in to access the application.
- **Admin Verification**: New users are initially restricted from booking rooms until an admin verifies their identity to prevent bot activity.
- **Room Booking**: Once verified by an admin, users can book rooms through the application.

## How It Works

1. **User Registration and Login**:
    - Users must create an account and log in to access the application features.
    - After logging in, users can view available rooms but cannot book them until verified by an admin.

2. **Admin Verification**:
    - An admin reviews new user accounts to ensure they are legitimate.
    - The admin updates the user's status to "verified," allowing them to book rooms.

3. **Room Booking**:
    - Verified users can book rooms through the application.
    - The booking process ensures secure and efficient reservations.
