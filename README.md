## FACIAL ATTENDENCE SYSTEM WITH THE HELP OF OpenCV.

# Overview of  the project:

The Smart Face Attendance System is an AI-powered solution that automates attendance tracking using facial recognition. This project utilizes OpenCV for face detection and a K-Nearest Neighbors (KNN) classifier for face recognition. The system captures images, trains a model with known faces, and logs attendance in CSV format.

## Features:

Real-time face detection using OpenCV's haarcascade_frontalface_default.

Face recognition using KNN for accurate identification.

Automated attendance logging with timestamps in CSV format.

Text-to-speech confirmation upon successful attendance.

## HOW TO USE:
Run Add_faces.py and enter the person's name.

The camera captures face images and stores them faces_data.pkl.

Run test.py to start real-time face recognition.

When a registered face is detected, it logs attendance in Attendance_{date}.csv.

Press 'o' to confirm attendance and 'q' to quit.

If Attendence is taken your system sounds "Attenddance Taken".


