# Hospital Management System

## Overview

The Hospital Management System is a Java-based application designed to manage patients, doctors, and appointments in a hospital setting. This console-based system interacts with a MySQL database to perform operations such as adding patients, viewing patient and doctor information, and booking appointments.

## Features

- **Add Patients**: Input and store new patient details including name, age, and gender.
- **View Patients**: Retrieve and display a list of all registered patients.
- **View Doctors**: Retrieve and display a list of all registered doctors.
- **Book Appointments**: Schedule appointments by selecting a patient and a doctor and specifying the appointment date. The system ensures doctor availability before booking.
- **Database Integration**: Uses JDBC to connect to a MySQL database for data management.

## Technologies Used

- **Java**: The main programming language used for application logic.
- **JDBC**: Java Database Connectivity API for interacting with the MySQL database.
- **MySQL**: Relational database management system for data storage.

## Installation and Setup

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/hospital-management-system.git
   cd hospital-management-system
Set Up MySQL Database

Ensure MySQL is installed and running.

Create a database named hospital using the following command in the MySQL shell:
CREATE DATABASE hospital;
Create the necessary tables in the hospital database. 
You can use the provided SQL schema or create your own tables as required.
Edit the HospitalManagementSystem.java file to update the database connection details (URL, username, and password):

Java
private static final String url = "jdbc:mysql://localhost:3306/hospital";
private static final String username = "root";
private static final String password = "yourpassword";

Compile and Run
Compile the Java files using the MySQL JDBC connector:

-cp .;path/to/mysql-connector-java.jar HospitalManagementSystem.java Patient.java Doctor.java

Run the application:

bash
-cp .;path/to/mysql-connector-java.jar HospitalManagementSystem

Usage

Add Patients: Select option 1 to input new patient details.
View Patients: Select option 2 to list all registered patients.
View Doctors: Select option 3 to list all registered doctors.
Book Appointments: Select option 4 to schedule an appointment by specifying patient ID, doctor ID, and appointment date.
Contributing
Contributions are welcome! If you want to improve the functionality, fix bugs, or add new features, please fork the repository, make changes, and submit a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Contact
For questions or support, please contact amanyadav4048@gmail.com or open an issue on this repository.

markdown

### Notes:
- **Replace** `yourusername` and `yourpassword` with your actual GitHub username and MySQL password.
- **Update** `path/to/mysql-connector-java.jar` with the path where the MySQL JDBC connector JAR file is located.
- **Provide** or **create** a LICENSE file if your project has specific licensing requirements.

This `README.md` file provides a clear overview of the project, instructions for installation
