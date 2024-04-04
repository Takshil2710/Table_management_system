# Table Reservation System

This Java application provides a simple command-line interface for managing table reservations in a restaurant.

## Features

- Reserve a table: Allows users to reserve a table by providing guest name, table number, contact number, and number of people.
- View Reservations: Displays a list of current reservations including reservation ID, guest name, table number, contact number, and reservation date.
- Get Table Number: Retrieves the table number for a given reservation ID and guest name.
- Update Reservations: Allows users to update existing reservations by providing a reservation ID and updating the guest name, table number, and contact number.
- Delete Reservations: Allows users to delete existing reservations by providing a reservation ID.

## Prerequisites

- Java Development Kit (JDK) installed on your machine.
- MySQL Database Server installed and running locally.
- MySQL Connector/J library added to the project (already included in the provided code).

## Setup

1. Clone this repository to your local machine:

2. Open the project in your preferred Java IDE (e.g., IntelliJ IDEA, Eclipse).

3. Import the MySQL Connector/J library into your project.

4. Set up the MySQL Database:
   - Create a new database named `table_db`.
   - Execute the provided `table_reservations.sql` script to create the `reservations` table.

5. Update the MySQL connection details in the `TableReservationSystem` class:
   - Replace `username` and `password` with your MySQL database credentials.

6. Build and run the application.

## Usage

- Upon running the application, you'll be presented with a menu to perform various operations:
  1. Reserve a table
  2. View Reservations
  3. Get Table Number
  4. Update Reservations
  5. Delete Reservations
  0. Exit

- Follow the prompts to perform your desired operation.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
