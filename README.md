Virtual Mouse Control Using Hand Gestures

Overview
This project allows you to control your mouse pointer using hand gestures captured via a webcam. It leverages Mediapipe, OpenCV, and PyAutoGUI/Pynput for real-time gesture recognition and mouse control.

Features
* Move the mouse pointer using hand movements.
* Perform mouse clicks using predefined gestures (e.g., pinch or finger gestures).
* Real-time hand tracking with minimal latency.
* Works with standard webcam.

Technologies Used
* Python 3.11
* OpenCV – For video capture and frame processing.
* Mediapipe – For hand landmark detection.
* Pynput / PyAutoGUI – For controlling mouse movements and clicks.
* NumPy – For coordinate calculations.

Installation

* Clone this repository or download the project.
	git clone <repository-url>
	cd live_mouse_control_using_hand_gestures

* Create a virtual environment:
	python -m venv .venv

* Activate the virtual environment:
	.venv\Scripts\activate  # Windows
	source .venv/bin/activate  # Linux/Mac

* Install the required packages:
	pip install --upgrade pip
	pip install opencv-python mediapipe pynput pyautogui numpy

Usage
1. Activate the virtual environment (if not already active).
2. Run the main script:
3. python main.py
4. A window will open showing your webcam feed.
5. Control the mouse using your hand gestures.
6. Press �ctrl+c� or close the window manually to stop the program.

Notes
* Ensure your webcam is working correctly.
* The program works best under good lighting conditions.
* Some warnings from TensorFlow/Mediapipe may appear; they do not affect functionality.

Future Improvements
* Add gesture-based scroll support.
* Multi-hand support.
* Customizable gesture mapping.
