﻿# Timberman-Bot
Screen Capture and Object Detection with Automated Controls
This project captures screenshots from specific areas of your screen, processes them using a YOLO-based object detection model, and automates keyboard inputs based on the detected objects. The script can be useful for various automation tasks that involve monitoring screen activity and responding to specific visual cues.

Features
Screen Capture: Captures screenshots from predefined areas on the screen.
Object Detection: Uses a YOLOv8 model to detect objects in the captured images.
Automated Key Presses: Simulates keyboard input based on detected objects.
Image Saving: Saves captured images with corrected colors for further processing.
Requirements
Before running the scripts, ensure you have the following installed:

Python 3.8+
MSS (for screen capture)
OpenCV (for image processing)
NumPy (for numerical operations)
PyAutoGUI (for simulating keyboard presses)
YOLOv8 (for object detection)
UUID (for unique file names)
Keyboard (for keyboard event detection)
Installation
Clone this repository:

bash
Skopiuj kod
git clone https://github.com/yourusername/screen-capture-automation.git
cd screen-capture-automation
Install the required Python packages:

bash
Skopiuj kod
pip install -r requirements.txt
Make sure you have your YOLO model (best.pt) in the project directory or modify the path to your model.

Customization
Screen Dimensions: Modify dimensionsLeft and dimensionsRight to capture different areas of the screen.
Object Detection Model: Replace best.pt with your trained YOLO model.
Key Presses: Customize the pyautogui.press() commands to simulate different keyboard inputs.
