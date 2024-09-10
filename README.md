Hospital Management System

This project is a Java-based Hospital Management System designed to manage patients, doctors, and appointments. It provides a simple console-based interface for interacting with the system and performing common operations such as adding patients, viewing patient and doctor information, and booking appointments.

Features:
Add Patients: Input and store patient details in the database, including name, age, and gender.
View Patients: Retrieve and display a list of all patients from the database.
View Doctors: Retrieve and display a list of all doctors from the database.
Book Appointments: Schedule appointments by selecting a patient and a doctor, and specifying the appointment date. The system checks doctor availability before booking.
Database Integration: Connects to a MySQL database for data storage and retrieval. Uses JDBC for database operations.
Technologies Used:
Java: Main programming language used for the backend logic.
JDBC: Java Database Connectivity API for interacting with the MySQL database.
MySQL: Relational database management system used to store patient, doctor, and appointment data.
Installation and Setup:
Clone the Repository:

bash
Copy code
git clone https://github.com/yourusername/hospital-management-system.git
cd hospital-management-system
Configure MySQL Database:

Ensure you have MySQL installed and running.
Create a database named hospital.
Create tables for patients, doctors, and appointments using the provided SQL schema (not included in this repo).
Update Database Credentials:

Modify the url, username, and password in the HospitalManagementSystem.java file to match your MySQL setup.
Compile and Run:

Compile the Java files:
bash
Copy code
javac -cp .;path/to/mysql-connector-java.jar HospitalManagementSystem.java Patient.java Doctor.java
Run the application:
bash
Copy code
java -cp .;path/to/mysql-connector-java.jar HospitalManagementSystem
Usage:
Add Patients: Choose option 1 from the menu to add new patient records.
View Patients: Choose option 2 to see a list of all registered patients.
View Doctors: Choose option 3 to view all doctors.
Book Appointments: Choose option 4 to schedule an appointment, ensuring that both the patient and doctor exist and that the doctor is available.
Contributing:
Feel free to fork the repository, make changes, and submit pull requests. Contributions are welcome to improve functionality, fix bugs, or add new features.

License:
This project is licensed under the MIT License - see the LICENSE file for details.

Contact:
For any questions or issues, please contact amanyadav4048@gmail.com or open an issue on this repository.
