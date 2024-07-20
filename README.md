# ParkCircle
Parking Space Tracking System
To run the code ,follow these steps shown in this [video](https://youtu.be/wh7HcrvCH6A)

# Park Circle Project Readme

Welcome to Park Sync, a project dedicated to enhancing the safety and sustainability of cities and human settlements through innovative technology. This readme provides an overview of the project structure, functionality, implementation details, and instructions for running the code. 🌆🌱

## Project Overview

Park Sync aims to optimize parking management using machine learning and computer vision techniques. By dynamically analyzing parking spaces, the system provides real-time insights into available slots, helping users efficiently locate parking spots and reducing congestion in urban areas. 🅿️🚗

## Directory Structure

- `main.py`: The main Python file responsible for executing the Park Sync system.
- `image_recognition/`: Directory containing modules for image recognition using TensorFlow.
- `data/`: Directory housing CSV files and other data generated by the system. 📁📊

## Activation

To activate Park Sync, run `main.py`. This script initiates the system, enabling dynamic functionality. 🚀

## Features

### Image Recognition

Park Sync utilizes TensorFlow for image recognition, accurately detecting parking slots within designated areas. 🖼️🔍

### User Interface

Upon activation, the user interface displays statistics, including empty slots, filled slots, and total available slots within the parking area. 📊🖥️

### Data Processing

Data fetched from the image recognition model is processed and stored in CSV format for easy analysis and retrieval. 📝🔄

## Implementation Details

### Main Python File

- Integration of OpenCV and TensorFlow libraries for image processing and machine learning functionalities.
- Output data from the machine learning model is saved in CSV format for further analysis.
- Variables such as true/false values indicating parking availability and coordinates of parking slots are included in the output. 🐍📦

### Video Input

The system operates on video input, analyzing parking spaces in real-time to provide up-to-date information on slot availability. 🎥🚦

## How to Run the Code

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Create a virtual environment using `python -m venv venv`.
4. Activate the virtual environment:
   - On Windows: `venv\Scripts\activate`
   - On macOS and Linux: `source venv/bin/activate`
5. Install the required dependencies using `pip install -r requirements.txt`.
6. Ensure you have Python installed on your system.
7. Navigate to the directory containing `main.py`.
8. Run the command `python main.py` to activate Park Sync.

## Conclusion

Park Sync represents a significant step towards creating safer and more sustainable urban environments. By leveraging advanced technologies, the project aims to streamline parking management and enhance overall urban mobility. 🏙️🔗

For any inquiries or contributions, please contact [pratikswayal123@gmail.com ].

Thank you for your interest in Park Circle! Together, let's build smarter cities for a brighter future. 🌟🏙️
