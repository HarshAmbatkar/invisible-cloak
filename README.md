🔵 Blue Cloak Effect
This project implements an "invisibility cloak" effect using OpenCV, making blue-colored objects appear transparent by replacing them with a static background.

📝 Features
1)Uses OpenCV to process real-time webcam feed.
2)Detects blue-colored objects and replaces them with a background frame.
3)Applies noise reduction and dilation to improve mask accuracy.
4)Runs efficiently on most computers with a webcam.

🚀 How It Works
1)Captures an initial background frame.
2)Continuously reads frames from the webcam.
3)Converts frames to HSV color space to detect blue.
4)Creates a binary mask to separate blue regions.
5)Blends the detected area with the background frame.
6)Displays the final output where blue-colored objects appear invisible.

🎮 Controls
Press 'q' to exit the program.

📌 Requirements
1)Python 3.x
2)OpenCV (opencv-python)
3)umPy (numpy)
4)A webcam


🏆 Credits
Developed by Harsh ambatkar
Inspired by invisibility cloak effects using OpenCV.
