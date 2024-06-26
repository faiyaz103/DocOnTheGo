# DOC on the GO

## About

**DOC on the GO** is an object-oriented C++ project designed to manage doctor appointments and database operations seamlessly. This application allows administrators to maintain a doctor database by adding, editing, and removing doctor records. Additionally, patients can use the system to find doctors and schedule appointments efficiently. This project is made under the course **Object Oriented Programming Laboratory (CSE 2102)** associated with **Khulna University of Engineering & Technology**.

### Features

- **Admin Panel:**
  - **Login Authentication:** Secure access to the admin panel with email and password.
  - **Doctor Database Management:** Admins can add, edit, and remove doctor records.
  - **View Doctor List:** Admins can view the entire list of doctors and their details.

- **Patient Interface:**
  - **View Doctor List:** Patients can view available doctors and their details.
  - **Schedule Appointments:** Patients can schedule appointments with doctors based on the available visiting hours.

### Functionalities

1. **Admin Functionalities:**
   - **Add Doctor:** Add new doctors to the database with details like code, name, department, fees, and visiting hours.
   - **Edit Doctor:** Modify existing doctor details in the database.
   - **Remove Doctor:** Remove doctor records from the database.
   - **View Doctor List:** Display all doctors and their details.

2. **Patient Functionalities:**
   - **View Doctor List:** Display all available doctors and their details.
   - **Make Appointment:** Schedule an appointment with a selected doctor by entering the doctor code and patient details.

### File Handling

The project utilizes file handling to maintain persistence in the doctor database and patient appointments:
- **docinfo.txt:** Stores doctor details including code, name, department, fees, and visiting hours.
- **receipt.txt:** Generates a receipt for patient appointments with details of the patient and the scheduled appointment.

### How to Use

1. **Admin Access:**
   - Select the "Use as Admin" option.
   - Login with the email: `doctor@email.com` and password: `doctor`.
   - Manage doctor database by selecting appropriate options from the admin panel.

2. **Patient Access:**
   - Select the "Use as a Patient" option.
   - View available doctors and schedule appointments by entering the doctor code and your details.

### Code Structure

- **menu:** Displays the main menu and directs users to admin or patient functionalities.
- **admin:** Displays admin panel and provides options to manage doctor database.
- **patient:** Displays patient interface and provides options to view doctors and schedule appointments.
- **add:** Allows admins to add new doctors to the database.
- **edit:** Allows admins to modify existing doctor records.
- **rem:** Allows admins to remove doctor records from the database.
- **list:** Displays the list of all doctors in the database.
- **finddoc:** Facilitates appointment scheduling for patients.

This project demonstrates the application of object-oriented programming concepts, file handling, and basic user authentication to create a functional and user-friendly doctor appointment system.
