				                         Attendance System Using Face Recognition

Table of Contents:-

Introduction
Features
Installation
Usage
Dependencies


Introduction:-
The Attendance System using Face Recognition is a project designed to automate the process of marking attendance using facial recognition technology. By leveraging advanced image processing and machine learning techniques, this system provides an efficient and accurate method for tracking attendance. The system uses the InsightFace model for face detection and facial features extraction, ensuring high accuracy and performance.

Features:-

User Management: Allows for adding user profiles.

![Screenshot (764)](https://github.com/alamrehan1234/attendance-system-face-recognition/assets/122749995/2c0f4ba0-5106-453d-8201-f8419e5a8afa)

Face Detection and Recognition: Automatically detects and recognizes faces in real-time.

![Screenshot (765)](https://github.com/alamrehan1234/attendance-system-face-recognition/assets/122749995/920b3be2-6bdb-4280-8d2c-148f0c6d21cc)

Attendance Logging: Logs attendance data to a Redis cloud database with timestamps.

![Screenshot (767)](https://github.com/alamrehan1234/attendance-system-face-recognition/assets/122749995/f514dd29-dca3-494e-8873-8be87917437c)


Reporting: Generates attendance reports for different time periods.
Web Interface: User-friendly web application built with Streamlit for interaction.

Installation:-

Prerequisites
Ensure you have the following installed on your system:

-Python 3.10.9
-Visual Studio Code (or any other preferred IDE)

#Steps

- Download the ZIP file containing the project from the provided source.
- Extract the ZIP file to your desired directory.
- Navigate to the Project Directory:

	cd path/to/your/extracted/project

- Create a Virtual Environment:

    	python -m venv attendance_system

- Activate the Virtual Environment:

	attendance_system\Scripts\activate

- Install Dependencies:

	pip install -r requirements.txt


Set Up the Database:-

Configure your Redis cloud database and update the connection settings in the project.

Run the Application:

	streamlit run Home.py

Usage:-

The web application has a home page with links to the following pages:

Real-Time Prediction:
Recognize faces and mark attendance in real-time using the camera.
Registration:
Register new users by capturing their Name, Role ie (Student , Teacher) and facial features.
Report Generation:
Generate and view attendance reports for different time periods.

Dependencies:-

numpy,
pandas,
matplotlib,
scipy,
jupyter,
opencv-python,
redis,
insightface,
onnxruntime,
sklearn,
scikit-learn,
InsightFace (for face detection and facial features extraction),
Redis (cloud database),
Visual Studio Code (IDE),
Streamlit (for creating web app)


This README provides a clear and concise overview ofthe project, including setup instructions for the virtual environment and how to run the application.
