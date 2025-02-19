Face Recognition Attendance System 
This project implements a face recognition-based attendance system using Python, OpenCV, and XAMPP. The system captures images of students and teachers, processes them, and marks attendance by recognizing faces in real-time. It stores attendance records in a MySQL database through a web interface built with HTML, CSS, JS, PHP, and SQL.

Features

Face Recognition: Detects and recognizes faces using OpenCV and the face_recognition library.
Real-Time Attendance: Marks attendance in real-time through a web interface.
Multiple Camera Integration: Uses a laptop camera for student attendance and a USB camera for teacher attendance.
Database Management: Stores attendance records in a MySQL database using XAMPP.
Automated Notifications: Sends WhatsApp messages and Telegram bot notifications when attendance is marked.
Web Interface: A user-friendly web interface to view attendance records. Technologies Used Backend:
Python: Core logic for face recognition and attendance marking.
OpenCV: For image and video processing.
Face_Recognition: For face detection and recognition.
MySQL: Database to store attendance records.
PHP: Server-side logic for handling database operations. Frontend:
HTML/CSS/JavaScript: To create a responsive and interactive user interface.
XAMPP: Provides the Apache web server and MySQL for database management. Hardware:
Laptop Camera: Used to capture images for face recognition (for students).
USB Camera: Captures images for teacher attendance.
Installation Prerequisites: Python XAMPP (Apache, MySQL)

Step-by-Step Setup:

Clone the Repository: git clone https://github.com/Mahesh72003/Face-Recognition-Attendance-Python-and-xampp cd Face-Recognition-Attendance-Python-and-xampp
Install Python Dependencies: pip install -r requirements.txt
Set Up XAMPP: Start Apache and MySQL services in XAMPP. Import the attendance_db.sql file to create the required database and tables.
Run the Face Recognition Script:
Access the Web Interface: Navigate to http://localhost/Face-Recognition-Attendance-Python-and-xampp/Web/index.html to view attendance records and manage the system.

Usage

Use the camera to capture images of students and teachers.
Run the face recognition system to identify individuals and mark attendance.
View attendance records via the web interface.
Automatically send notifications through WhatsApp and Telegram upon successful attendance marking.

Future Enhancements
Add an admin dashboard to manage users and view detailed attendance analytics.
Improve face recognition accuracy with additional training data.

Contributions Contributions are welcome! Feel free to fork the repository and submit pull requests.
