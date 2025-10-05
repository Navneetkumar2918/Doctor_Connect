About
Doctor In Your Mobile is a console-based, object-oriented C++ project developed to simplify and digitize the process of managing doctor appointments and healthcare professional records. This application is thoughtfully designed to serve both administrators and patients, offering an efficient and user-friendly interface to handle medical scheduling and information access.

This project is developed as a part of the Object Oriented Programming Laboratory (CSE 212) course under the Department of Computer Science and Engineering, National Institute of Technology, Silchar.

Features
Admin Panel:

Secure Login Authentication: Only authorized personnel can access the admin dashboard using a valid email and password combination, ensuring the integrity of the system.

Doctor Database Management: Admins can easily add new doctor records, update existing details, or remove outdated or incorrect entries from the database, enabling smooth record maintenance.

Doctor Directory Access: Admins have the ability to view the complete list of registered doctors, including their specialization, consultation fees, and visiting hours — all displayed in a clean and readable format.

Patient Interface:

View Doctors List: Patients can view all available doctors, including their names, departments, consultation charges, and visiting time slots — helping them choose the right specialist with ease.

Book Appointments Effortlessly: Patients can schedule appointments by selecting the doctor’s code and entering their personal details. A confirmation receipt is generated with all necessary visit information.

Functionalities
Admin Functionalities:

Add Doctor Record: Seamlessly register a new doctor by entering essential details like unique code, full name, specialization/department, consultation fee, and visiting hours.
Edit Doctor Information: Easily update any existing doctor’s information in the database to keep records accurate and up-to-date.
Remove Doctor: Delete a doctor’s record permanently from the system in case of incorrect entry or if the doctor is no longer available.
View Doctor Directory: Instantly view a well-formatted list of all registered doctors along with their specialization, fees, and availability.
Patient Functionalities:

**Explore Doctor Directory:**Patients can easily browse through the complete list of available doctors, along with their names, specializations, consultation fees, and visiting hours — all in a well-organized format.
Book a Consultation Appointment: Patients can quickly schedule an appointment with their preferred doctor by entering the doctor's unique code and providing basic details like name and contact number. Once confirmed, an appointment receipt is generated instantly.
File Handling
To ensure data persistence and smooth functioning of the application across sessions, this project effectively employs file handling in C++. All critical data such as doctor records and appointment details are securely stored in text files:

docinfo.txt: Acts as the primary doctor database, storing essential information such as:
Doctor Code
Full Name
Department / Specialization
Consultation Fees
Visiting Hours
receipt.txt: Used to generate and save appointment receipts for patients after successful scheduling. It contains.
Patient Name
Contact Number
Appointed Doctor’s Code
Visiting Time
Fees
This modular approach ensures that both admin and patient interactions with the system are efficient, reliable, and backed by permanent data storage.

How to Use
Admin Access:
Select Use as Admin from the main menu.
Login Credentials: Email: doctorinyourmobile@email.com Password: Appoint_a_Doctor

Once logged in, the admin panel offers the following options:

Add a new doctor to the system.
Edit existing doctor details.
Remove a doctor from the database.
View the complete list of registered doctors with their details.
Patient Access:
Patients can easily browse available doctors and schedule a ppointments through a simple interface:

Select Use as a Patient from the main menu.

View the complete list of doctors along with: Doctor Name Department Consultation Fee Visiting Hours

Make an Appointment by: Entering the doctor’s code. Providing your personal details (name and contact number).

A receipt will be generated and saved for confirmation.

Code Structure
menu: Displays the main interface allowing the user to select between Admin access, Patient access, or exit. It routes the flow of the program accordingly.
admin: Opens the admin panel after successful login. Allows the administrator to manage doctor data — add, modify, delete, or view records.
patient: Provides the patient interface with options to view the list of available doctors and schedule appointments.
add: Enables the administrator to add a new doctor to the system. Collects information such as doctor code, name, specialization, consultation fee, and visiting hours.
edit: Allows modification of an existing doctor’s details using the doctor code as a reference.
rem: Removes a doctor's record from the database permanently, based on the entered doctor code.
list: Displays a formatted table of all doctors in the database including their names, departments, consultation fees, and available hours.
finddoc: Facilitates appointment booking for patients. After selecting a doctor by code, the patient provides their personal details and receives a receipt confirmation.
This project effectively showcases the practical implementation of Object-Oriented Programming (OOP) principles combined with file handling and basic user authentication to build a robust and user-friendly Doctor Appointment Management System.

It emphasizes:
Encapsulation through class-based design for handling admin and patient functionalities.

Data persistence using file I/O operations for storing doctor records and patient appointments.

User interaction through a clean and intuitive terminal-based interface, enabling both administrators and patients to manage healthcare data with ease.

The system not only reinforces foundational programming concepts but also simulates a real-world application with meaningful societal impact — allowing streamlined medical appointment scheduling and efficient doctor database management
