##**AI Virtual Mouse**

 
 ##Overview

AI Virtual Mouse is a hand-tracking-based system that allows users to control the mouse pointer using hand gestures. This project leverages OpenCV, MediaPipe, and PyAutoGUI to detect hand movements and perform actions like clicking, scrolling, and dragging.

## Features

- Move the mouse cursor using the index finger.
- Left-click when the index finger and thumb come close together.
- Right-click when the middle finger and thumb come close together.
- Scroll up when the index finger is above the middle finger.
- Scroll down when the index finger is below the middle finger.
- Drag and drop when the ring finger and thumb come close together.

## Technologies Used

- OpenCV
- MediaPipe
- PyAutoGUI
- NumPy

## Installation

### Prerequisites

Make sure you have Python installed on your system. You can install the required dependencies using:

```sh
pip install opencv-python mediapipe pyautogui numpy
```

## Usage

1. Run the script:

```sh
python ai_virtual_mouse.py
```

2. Ensure your webcam is on.
3. Control the mouse using hand gestures.
4. Press 'q' to exit the program.

## How It Works

1. The webcam captures the video feed.
2. MediaPipe detects hand landmarks in real time.
3. The index finger's position is mapped to screen coordinates for cursor movement.
4. Different finger combinations trigger various mouse actions.
5. PyAutoGUI executes corresponding system actions.

## Troubleshooting

- Ensure you have good lighting for better hand detection.
- If gestures are not detected correctly, try adjusting your hand position.
- Make sure all dependencies are installed correctly.

## License

This project is open-source and available under the MIT License.

## Contributing

Feel free to contribute to this project by submitting issues or pull requests.

## Author

Aravinnth

