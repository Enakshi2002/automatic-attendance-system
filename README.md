
# Automated Attendance System by Face Recognition

## Overview

The *Automated Attendance System* utilizes *Face Recognition Technology* to efficiently and accurately record attendance with minimal human intervention. It is implemented using Python and libraries like *OpenCV, **face_recognition, and **openpyxl*. The system captures a live video feed, identifies individuals using facial encodings, and updates their attendance in real time.

## Features

- *Face Recognition:* Identifies individuals using their unique facial features.
- *Automated Attendance Marking:* Updates attendance in an Excel sheet for recognized faces.
- *Real-Time Processing:* Processes live video feed from a webcam for seamless operation.
- *Minimal Training Requirement:* Requires only a single image per individual for recognition.
- *Accuracy:* Built with robust algorithms for high accuracy and reliability.

## Technologies Used

- *Programming Language:* Python
- *Libraries:*
  - [OpenCV](https://opencv.org/) - Computer vision tasks
  - [face_recognition](https://github.com/ageitgey/face_recognition) - Simplified face recognition
  - [numpy](https://numpy.org/) - Numerical computations
  - [openpyxl](https://openpyxl.readthedocs.io/) - Excel file handling
  - [PIL](https://pillow.readthedocs.io/) - Image processing
  - [datetime](https://docs.python.org/3/library/datetime.html) - Timestamp management

## Installation

1. Clone the repository:
   bash
   git clone https://github.com/baisali14/Automated_Attendance_System.git
   cd Automated_Attendance_System
   
2. Install the required dependencies:
   bash
   pip install opencv-python face_recognition numpy openpyxl pillow
   
3. Ensure you have a webcam connected to your system.

## How It Works

1. *Image Preprocessing:* 
   - Store individual images in the ImageAttendance folder. Each file's name should represent the individual.
2. *Facial Encoding:*
   - Encodings are created from the stored images to identify individuals.
3. *Live Recognition:*
   - A live webcam feed captures and processes frames to detect faces and match them against the stored encodings.
4. *Attendance Marking:*
   - Matched individuals' names are displayed, and their attendance is recorded in Attendance.xlsx with timestamps.

## Usage

1. Run the main script:
   bash
   python main.py
   
2. Allow access to the webcam.
3. The system will automatically recognize faces from the live feed and update the attendance file.

## Future Enhancements

- *Multi-Camera Support:* Enable monitoring across multiple locations simultaneously.
- *Dynamic Face Addition:* Add new faces to the system during runtime.
- *Real-Time Monitoring:* Display live attendance updates.
- *Deep Learning Integration:* Incorporate advanced CNN models for improved accuracy.
- *System Integration:* Connect with Learning Management Systems (LMS) or HR Management Systems (HRMS).

