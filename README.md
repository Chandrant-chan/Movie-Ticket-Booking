# Movie Ticket Booking System

This is a console-based Movie Ticket Booking System built using Python. The system allows users to browse available movies, book tickets, manage bookings, and view ticket details.

## Features

- User registration and authentication
- Browse available movies and showtimes
- Book tickets for selected movies
- View booking history
- Cancel bookings
- Search for movies by title or showtime

## Installation

1. Clone the repository and navigate to the project directory.
2. Install the necessary dependencies using:
   ```sh
   pip install -r requirements.txt
   ```
3. Set up a SQLite or PostgreSQL database and configure the connection settings in a `.env` file.
4. Run the application with:
   ```sh
   python main.py
   ```

## Usage

- Register as a new user or log in with existing credentials.
- Browse a list of available movies and showtimes.
- Select a movie and book tickets by choosing the number of seats.
- View a list of all booked tickets.
- Search for movies by title or showtime.
- Cancel a booking if needed.

## Database Schema

The database consists of three main tables:

- **users**: Stores user information such as name, email, and password.
- **movies**: Stores movie details, including title, duration, and showtime.
- **bookings**: Links users with movie tickets, storing booking details such as seat number and transaction status.

## Contributing

Contributions are welcome! Please fork the repository, create a new branch, commit your changes, and create a pull request.

## License

This project is licensed under the MIT License.

## Contact

For any inquiries or feedback, feel free to reach out via GitHub.

