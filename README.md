# Face Recognition Attendance System

This project implements a real-time face recognition attendance system using a webcam. It detects faces, recognizes known individuals, and logs their attendance in a CSV file.

## Requirements

Install the following packages:
pip install face_recognition opencv-python numpy


## Setup

1. Create a `photos` directory in the project root.
2. Add photos of known individuals to the `photos` directory (e.g., jobs.jpg, tata.jpg, sadmona.jpg, tesla.jpg).

## Usage

Run the script:
python program.py


- Press 'q' to quit the program.
- Attendance will be logged in a CSV file named with the current date.

## Features

- Real-time face detection and recognition
- Attendance logging with timestamps
- Visual display of recognized individuals

## Note

Ensure your webcam is connected and functioning properly before running the script.
