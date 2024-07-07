# Hospital Management System

## Project Overview

This project is a Hospital Management System implemented using PHP and CSS with SQL as the backend. The website is a one-page application with a scroll-down feature, providing sections for services offered by doctors, admin, patients, and doctors with respective login functionalities. Patients can make appointments and book slots with doctors, who in turn can set their available slots. The system also includes a specialist selection feature during booking.

## Project Structure

- **assets/**: Contains CSS, images, and other static assets.
- **includes/**: Contains PHP files for database connection and other utilities.
- **templates/**: Contains HTML templates.
- **index.php**: Main entry point for the application.
- **README.md**: Project documentation.

## Getting Started

### Prerequisites

To run this project, you'll need to have the following installed:

- XAMPP (or any other local server with PHP, Apache, and MySQL support)

### Installation

1. **Download and extract the project files:**

   Download the project files and extract them into the `htdocs` folder located in your XAMPP installation directory (usually `C:\xampp\htdocs`).

2. **Start XAMPP Control Panel:**

   Open XAMPP Control Panel and start the Apache and MySQL services.

3. **Set up the Database:**

   - Open your web browser and navigate to `http://localhost/phpmyadmin`.
   - Create a new database named `hospital_management`.
   - Import the provided SQL file (`hospital_management.sql`) into the newly created database.

4. **Update Database Configuration:**

   Open the `includes/db_connect.php` file and update the database connection details if necessary (e.g., username, password).

### Running the Project

1. **Open the Application:**

   In your web browser, navigate to `http://localhost/hospital_management`.

2. **Login and Explore:**

   Use the provided admin, patient, and doctor login credentials to explore the features of the application.

## Features

### Admin Section

- **Admin Login:**
  - Manage doctors and patient records.
  - View all appointments.
  - Set available slots for doctors.

### Doctor Section

- **Doctor Login:**
  - View and manage their appointments.
  - Set available slots for patients to book.

### Patient Section

- **Patient Login:**
  - Book appointments with doctors.
  - View their appointment history.
  - Select specialists during booking.

### Services Section

- Displays the services offered by doctors at the hospital.

## Using the System

### Making an Appointment

1. **Login as Patient:**
   - Navigate to the patient login section and log in using patient credentials.

2. **Book an Appointment:**
   - Choose a doctor or specialist from the list.
   - Select an available slot.
   - Confirm the booking.

### Setting Available Slots (Doctor)

1. **Login as Doctor:**
   - Navigate to the doctor login section and log in using doctor credentials.

2. **Set Slots:**
   - Navigate to the slot management section.
   - Set available slots for patients to book.

## Viewing the Backend

1. **Open phpMyAdmin:**
   - In your web browser, navigate to `http://localhost/phpmyadmin`.

2. **Access the Database:**
   - Select the `hospital_management` database to view and manage the backend data.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, please create a pull request or open an issue.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the authors of the libraries and tools used in this project.
- Special thanks to the data providers for making this project possible.

Feel free to reach out if you have any questions or need further assistance. Happy coding!

---

By following these instructions, you'll be able to execute the code and utilize the Hospital Management System.
