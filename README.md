📚 IoT-Based Smart Attendance System using NFC & Face Recognition
Manual attendance systems are often time-consuming, error-prone, and vulnerable to proxy attendance. This project presents an IoT-based Smart Attendance System that integrates NFC technology and Face Recognition, offering a secure and automated solution for student attendance management.

🚀 Project Overview
This system uniquely identifies each student using:

An NFC card (for authentication)

Face recognition (for verification)

Both credentials are required before attendance is successfully marked.

💡 Key Features
🧠 Face Recognition using OpenCV and Python

📶 NFC-based Identification with Raspberry Pi

☁️ Real-Time Cloud Sync using Firebase Firestore

📊 Interactive Dashboard built with Streamlit

🔒 Eliminates proxy attendance and ensures accurate records

📈 Monthly reports and attendance summaries with visual analytics

🛠️ Technologies Used
Hardware: Raspberry Pi, NFC Reader

Software: Python, OpenCV, Firebase Firestore, Streamlit

Libraries: face_recognition, firebase-admin, pandas, matplotlib

📟 How It Works
A student taps their NFC card on the Raspberry Pi-based reader.

The system captures the student's image using a camera module.

The face is verified using a pre-registered dataset.

Upon successful verification, attendance is marked and synced to the cloud.

Faculty can monitor and manage records via the Streamlit dashboard.

📊 Streamlit Dashboard
Faculty can:

View daily/monthly attendance reports

Search by roll number or date

Analyze data using graphs and tables

Export attendance data if needed

🔧 Scalability & Benefits
Easily scalable for large institutions

Improves transparency and reduces manual errors

Secure and easy-to-use interface for both students and faculty
