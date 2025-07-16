# Real-time Object Tracker
This project implements a real-time object tracking application using a webcam feed. It allows users to select an object of interest in the video stream, and then the system automatically tracks its movement across subsequent frames. This is ideal for applications requiring continuous monitoring of a specific object in a live video.

Features
Interactive Object Selection: Manually select the target object in the initial frame.

Real-time Tracking: Continuously tracks the selected object as it moves.

Visual Feedback: Displays a bounding box around the tracked object and indicates tracking status (tracking/lost).

FPS Display: Shows the frames per second (FPS) of the video processing.

## How to Use
Start the application: Upon execution, a window displaying your webcam feed will appear.

Select the object: Use your mouse to draw a bounding box around the object you wish to track. Press Enter or Space to confirm your selection.

Observe tracking: The system will then attempt to follow the selected object in real-time. A green "Tracking" message will appear if successful, or a red "Lost" message if the object is no longer detected.

Quit: Press the 'q' key to exit the application.

## Tools Used
- Python: The core programming language for the application logic.

- OpenCV (cv2): A powerful library for computer vision tasks, including video capture, image processing, and object tracking algorithms (specifically the MOSSE tracker).
