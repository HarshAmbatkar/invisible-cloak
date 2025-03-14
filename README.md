🔵 Blue Cloak Effect
This project implements an "invisibility cloak" effect using OpenCV, making blue-colored objects appear transparent by replacing them with a static background.

📝 Features
Uses OpenCV to process real-time webcam feed.
Detects blue-colored objects and replaces them with a background frame.
Applies noise reduction and dilation to improve mask accuracy.
Runs efficiently on most computers with a webcam.

🚀 How It Works
Captures an initial background frame.
Continuously reads frames from the webcam.
Converts frames to HSV color space to detect blue.
Creates a binary mask to separate blue regions.
Blends the detected area with the background frame.
Displays the final output where blue-colored objects appear invisible.

🎮 Controls
Press 'q' to exit the program.
📌 Requirements
Python 3.x
OpenCV (opencv-python)
NumPy (numpy)
A webcam


🏆 Credits
Developed by Harsh ambatkar
Inspired by invisibility cloak effects using OpenCV.
