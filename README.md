# AI Virtual Mouse Using Hand Gestures

This project creates a virtual mouse that can be controlled using hand gestures detected by a webcam. The AI Virtual Mouse utilizes computer vision techniques for hand tracking and gesture recognition to control mouse movements and perform actions such as clicks. It provides a hands-free interface for controlling the mouse using a camera.

## Features
- Hand tracking using **MediaPipe**.
- Gesture recognition for mouse movements and actions.
- Real-time mouse control using hand gestures like:
  - Moving the mouse pointer.
  - Left click with a pinching gesture.
  - Mouse scroll with specific gestures.

## Technologies Used
- **OpenCV**: For real-time video capture and image processing.
- **MediaPipe**: For hand detection and tracking.
- **PyAutoGUI**: To simulate mouse actions like movement and clicks.
- **Numpy**: For numerical operations and processing coordinates.

## How It Works
1. **Hand Tracking**: The webcam captures frames which are processed using MediaPipe to detect and track hands.
2. **Gesture Recognition**: The hand landmarks provided by MediaPipe are analyzed to identify gestures (e.g., pinching fingers for clicking, moving the index finger to move the cursor).
3. **Mouse Control**: The recognized gestures are used to simulate mouse movements and actions using PyAutoGUI.

## Installation

### Prerequisites
- Python 3.x
- A webcam

### Libraries
The required Python libraries can be installed using the following command:
```bash
pip install -r requirements.txt
