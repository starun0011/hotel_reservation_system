# Hotel Reservation System

## Project Overview

The Hotel Reservation System is a Java-based application designed to assist hotel receptionists in managing reservations. This system simplifies tasks such as booking new reservations, checking existing reservations, retrieving room numbers, updating details, and deleting reservations.

## Features

- **New Reservation:** Allows users to add new bookings by entering customer details and room preferences.
- **Check Reservation:** Search and view existing reservations by customer name or booking ID.
- **Get Room Number:** Retrieve the room number assigned to a specific guest based on their reservation.
- **Update Reservation:** Modify existing bookings, including room changes, guest information updates, and more.
- **Delete Reservation:** Remove bookings from the system as needed.

## Technologies Used

- **Java:** Core language used for developing the application logic.
- **JDBC (Java Database Connectivity):** Used to connect and interact with the MySQL database.
- **MySQL:** Database management system for storing and managing reservation, customer, and room data.

## Installation and Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/hotel-reservation-system.git
   ```
2. **Navigate to the Project Directory:**
   ```bash
   cd hotel-reservation-system
   ```
3. **Set Up the Database:**
   - Create a MySQL database named `hotel_reservation`.
   - Execute the provided SQL script (`database.sql`) to set up the necessary tables.

4. **Configure Database Connection:**
   - Update the database connection details (URL, username, password) in the Java code (`DatabaseConnection.java`).

5. **Compile and Run the Application:**
   ```bash
   javac Main.java
   java Main
   ```

## Usage

1. **Start the application.**
2. **Navigate through the menu** to add, update, or delete reservations as required.
3. **Follow on-screen instructions** to manage bookings efficiently.

## Future Enhancements

- Integration with a payment gateway for secure booking payments.
- Addition of a user-friendly graphical interface for improved usability.
- Implementation of email notifications for booking confirmations and updates.

## Contributing

Contributions are welcome! Please create an issue or pull request if you wish to contribute.
