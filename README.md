Overview
This project leverages advanced face recognition technology to simplify attendance tracking. The system uses OpenCV for facial recognition, HarCascade for face detection, and Streamlit for a sleek interface. It efficiently records punch-ins with a single press of 'O' and logs the data into a CSV file, ensuring accurate records with the help of the datetime package.

Features
Face Detection & Recognition: Utilizes OpenCV and HarCascade to detect and recognize employee faces.
Attendance Logging: Logs punch-in details such as name and timestamp into a CSV file.
Speech Feedback: Uses the Windows SAPI to provide verbal confirmation of attendance.
Streamlit Integration: Displays the attendance records in a user-friendly interface.
Customizable Background: Includes an option to display the captured video feed on a custom background.

Requirements
Python 3.x
OpenCV
NumPy
scikit-learn
pandas
Streamlit
win32com.client

Project Structure
employee_punching_system.py: Main script to run the face recognition and attendance system.
view_attendance.py: Script to view attendance records using Streamlit.
dataset/: Directory containing the face data and labels.
model/: Directory containing the face detection model.
Attendance/: Directory where attendance logs are saved.
This README file should provide a clear understanding of the project's functionality and how to set it up and use it.
