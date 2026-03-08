# College ERP System ##  WEBTECHFLY
# MERN Stack Based Academic Management System
# System Overview

The College ERP System is a web-based academic management platform developed using the MERN stack, which includes MongoDB, Express.js, React.js, and Node.js. The primary objective of the system is to digitalize and streamline the academic and administrative activities of educational institutions. The system provides a centralized platform where administrators, faculty members, and students can manage and access academic information efficiently.

The ERP system eliminates the dependency on manual record keeping and traditional paper-based management methods. Through this platform, institutional data such as student information, faculty records, attendance, subjects, and examination results can be managed in a secure and organized manner. The system ensures transparency, accessibility, and efficiency in academic operations.

# System Configuration and Setup

To run the College ERP system successfully, the project environment must be configured properly.
Create a .env file inside the server directory.
Copy the contents from the .env.example file into the newly created .env file.
Update the MONGODB_URI variable with the MongoDB Atlas connection string to establish database connectivity.
Open a terminal in the client folder and execute the following command to start the frontend application:
npm run start
Open another terminal in the server folder and execute the following command to start the backend server:
npm run start
After the server is successfully started, navigate to the following URL in the browser:
http://localhost:3000/login/adminlogin
During the first execution of the system, a default administrator account is automatically generated to enable system access.

# Default Admin Credentials:
Username: ADMDUMMY
Password: 123
These credentials can later be modified by the administrator through the profile management section.

# Technology Stack
The development of the College ERP system is based on modern web technologies that support scalable and efficient application development.
React.js – Used for building dynamic and responsive user interfaces for the frontend application.
Tailwind CSS – Utilized for designing modern and responsive user interface components with efficient styling.
MongoDB – A NoSQL database used for storing institutional data such as student records, faculty information, attendance data, and examination results.
Express.js – A backend web framework used for handling server-side logic, routing, and API development.
Node.js – Provides the runtime environment for executing JavaScript on the server side.
Redux – Used for managing application state in a structured and predictable manner.
Material UI Icons – Provides a collection of modern icons used in the user interface to improve visual design.
JSON Web Token (JWT) – Used for implementing secure user authentication and authorization mechanisms within the system.

# Key Features of the System
The College ERP system provides multiple functionalities for administrators, faculty members, and students.
Administrator Features
The administrator has full control over the system and can manage institutional operations. The administrator can update personal profile details, change passwords, and manage users within the system. The administrator can add, delete, or retrieve information related to students, faculty members, and other administrators. Additionally, the administrator has the authority to create and manage departments, subjects, and institutional notices that can be viewed by other users.

# Faculty Features
Faculty members can log into the system using secure authentication mechanisms. After logging in, faculty members can update their profile details and manage their passwords. Faculty members can record student attendance, create tests or examinations, and upload student marks for evaluation. These features allow faculty members to manage academic activities efficiently through the ERP platform.

# Student Features
Students can access the system using their login credentials and view their academic information. They can update their profile details and manage their passwords within the system. Students can check their attendance records, view examination marks, and access the list of subjects associated with their academic program.

# Authentication and Security
The system implements JWT-based authentication to ensure secure access for different types of users. Each user must authenticate through the login system before accessing the platform. This ensures that only authorized users can view or modify institutional data.

# User Interface and Validation
The system features a modern and user-friendly interface designed using React.js and Tailwind CSS. Form validation and error display mechanisms are implemented to guide users and prevent incorrect data entry.

# Future Enhancements
Although the current system provides essential ERP functionalities, several additional improvements can be implemented in future versions of the system.

# Future enhancements may include:
Mobile responsive design for better accessibility on smartphones and tablets.
Expansion of system modules beyond academic management, such as finance, library management, and hostel management.
Enhanced administrative controls for managing students, faculty members, departments, and subjects.
Advanced reporting and analytics features to support institutional decision-making.

# Preview
Admin

https://user-images.githubusercontent.com/90241373/156794210-af4db587-1aba-4289-9196-07f2e179d9bb.mp4

<br>

Faculty

https://user-images.githubusercontent.com/90241373/156794428-1a73579c-8116-45dd-bee4-140f3b6de2c8.mp4

<br>

Student

https://user-images.githubusercontent.com/90241373/156794474-1ba1d10e-30c8-4ce7-881b-520d7ab6aec6.mp4
