# Hospital Management System

## Project Overview

This Hospital Management System (HMS) is a one-page website designed with PHP and CSS, using SQL for the backend. The system provides a comprehensive solution for managing hospital services, including features for doctors, patients, and administrators. The site includes a scroll-down feature for easy navigation.

## Project Features

- **Admin Section:**
  - Login and manage hospital services.
  - View and manage appointments and schedules.

- **Doctor Section:**
  - Login and manage available slots.
  - View appointments made by patients.

- **Patient Section:**
  - Login and book appointments.
  - Select specialists and available slots for booking.

## Getting Started

### Prerequisites

To run this project, you'll need to have the following installed:

- XAMPP (or any other PHP development environment)

### Project Structure

- **htdocs/**: Contains the project files.
- **sql/**: Contains the SQL scripts for creating and populating the database.
- **README.md**: Project documentation.

### Setting Up the Project

1. **Download the project files:**

   Download the project files from the repository and extract them.

2. **Move the project to XAMPP htdocs:**

   Copy the project folder to the `htdocs` directory in your XAMPP installation directory.

3. **Start XAMPP:**

   Open the XAMPP Control Panel and start Apache and MySQL.

4. **Set up the Database:**

   - Go to the MySQL admin section by clicking on the `Admin` button in the XAMPP Control Panel.
   - Import the SQL script provided in the `sql/` directory to set up the database.

5. **Run the Project:**

   - Open your web browser and go to `http://localhost/[your-project-folder-name]`.
   - The website should now be accessible and ready to use.

### Using the System

1. **Admin Section:**

   - Login with admin credentials.
   - Manage doctor schedules and appointments.
   - View overall hospital management statistics.

2. **Doctor Section:**

   - Login with doctor credentials.
   - Add available slots for appointments.
   - View booked appointments.

3. **Patient Section:**

   - Login with patient credentials.
   - Book appointments by selecting specialists and available slots.
   - View upcoming appointments.

### Project Workflow

1. **Admin Management:**

   - Admin can log in to view and manage all hospital activities.
   - Admin can manage doctor schedules and view patient appointments.

2. **Doctor Management:**

   - Doctors can log in to update their availability.
   - Doctors can manage their appointment slots and view bookings.

3. **Patient Management:**

   - Patients can log in to book appointments with doctors.
   - Patients can select specialists and view available slots.
   - Patients can manage their appointment history.

## Backend Access

To view the backend:

1. Go to the MySQL admin section by clicking on the `Admin` button in the XAMPP Control Panel.
2. Navigate through the database to view tables and manage data directly.

## Conclusion

This Hospital Management System provides a robust and user-friendly interface for managing hospital services, ensuring a smooth and efficient process for administrators, doctors, and patients.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, please create a pull request or open an issue.

## Acknowledgments

- Thanks to the authors of the PHP and CSS libraries used in this project.
- Special thanks to the contributors and data providers for making this project possible.

Feel free to reach out if you have any questions or need further assistance. Happy coding!

---

By following these instructions, you'll be able to set up and run the Hospital Management System, ensuring a seamless management experience for all users.

