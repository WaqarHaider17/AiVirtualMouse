AI Virtual Mouse

The AI Virtual Mouse project offers a hands-free solution for controlling the mouse cursor using hand gestures captured via webcam. This project utilizes computer vision techniques and gesture recognition to interpret hand movements in real-time, allowing users to interact with their computers without physical input devices.

Features

- **Hand Tracking**: Utilizes OpenCV and MediaPipe to detect and track hand landmarks in the webcam feed.
- **Gesture Recognition**: Interprets hand gestures, such as finger movements and positions, to simulate mouse cursor movements and clicks.
- **Real-time Feedback**: Provides real-time visual feedback by overlaying hand landmarks and cursor movements on the webcam feed.
- **Dynamic Cursor Control**: Smoothly translates hand movements into cursor movements, offering a seamless user experience.
- **Customizable Parameters**: Allows users to adjust parameters like frame reduction and smoothing for personalized interaction.

Requirements

- Python 3.x
- OpenCV
- MediaPipe
- NumPy
- PyAutoGUI

Installation

1. Clone or download the repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the `AiVirtualMouseProject.py` script using Python.

Usage

1. Ensure your webcam is connected and functional.
2. Run the `AiVirtualMouseProject.py` script.
3. Position your hand within the webcam frame and perform gestures to control the cursor.
4. Use a single finger to move the cursor and two fingers to simulate mouse clicks.
5. Adjust parameters as needed for optimal performance.

License

This project is licensed under the [MIT License](LICENSE). Feel free to modify and distribute it according to your needs. Contributions are welcome!