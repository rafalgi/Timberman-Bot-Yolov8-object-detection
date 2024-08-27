# Timberman-Bot

# Screen Capture and Object Detection with Automated Controls

This project is designed to capture screenshots from specific areas of your screen, process them using a YOLO-based object detection model, and automate keyboard inputs based on the detected objects. It’s useful for various automation tasks that require monitoring screen activity and responding to specific visual cues.

## Features

- **Screen Capture**: Captures screenshots from predefined areas on the screen.
- **Object Detection**: Uses a YOLOv8 model to detect objects in the captured images.
- **Automated Key Presses**: Simulates keyboard input based on detected objects.
- **Image Saving**: Saves captured images with corrected colors for further processing.

## Requirements

Before running the scripts, ensure you have the following installed:

- **Python 3.8+**
- **MSS** (for screen capture)
- **OpenCV** (for image processing)
- **NumPy** (for numerical operations)
- **PyAutoGUI** (for simulating keyboard presses)
- **YOLOv8** (for object detection)
- **UUID** (for unique file names)
- **Keyboard** (for keyboard event detection)

## Installation

1. Clone this repository:

    ```bash
    git clone https://github.com/yourusername/screen-capture-automation.git
    cd screen-capture-automation
    ```

2. Install the required Python packages:

    ```bash
    pip install -r requirements.txt
    ```

3. Make sure you have your YOLO model (`best.pt`) in the project directory or modify the path to your model.

## Customization

- **Screen Dimensions**: Modify `dimensionsLeft` and `dimensionsRight` to capture different areas of the screen.
- **Object Detection Model**: Replace `best.pt` with your trained YOLO model.
- **Key Presses**: Customize the `pyautogui.press()` commands to simulate different keyboard inputs.
