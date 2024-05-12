# DLD-lab-opencv-project-virtual-mouse-face-recognation

Face-Controlled Virtual Mouse using OpenCV and MediaPipe

Description:
This project demonstrates how to control a virtual mouse using facial landmarks detected in real-time from a webcam feed. It utilizes OpenCV for video capture and display, MediaPipe for face landmark detection, and PyAutoGUI for mouse cursor control.

Requirements:
Python 3.x
OpenCV (cv2)
MediaPipe (mediapipe)
PyAutoGUI (pyautogui)

Installation:
1. Install Python
2. Install required Python libraries:
   
   pip install opencv-python mediapipe pyautogui
   

Usage:
1. Run the script "face_mouse_control.py".
   
   python face_mouse_control.py
   
2. Make sure your face is visible to the webcam.
3. Move your face to control the mouse cursor. The cursor will follow the movement of your face.
4. Blink your left eye to simulate a mouse click.

Notes:
- The script captures video from the default webcam. Make sure you have a webcam connected or adjust the video capture device index accordingly.
- The MediaPipe FaceMesh model detects 468 facial landmarks. You can adjust the landmark indices to suit your specific requirements.
- Adjust the threshold for left-eye blink detection according to your preferences and environmental conditions.

Author:
Team Name: Restart 
Team members: 
Assadujjaman(2017-14-05)
Mariyan Tanchangya(2017-14-47)

