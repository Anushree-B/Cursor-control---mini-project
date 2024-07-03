# CURSOR CONTROL USING HAND GESTURE RECOGNITION

**Introduction**

This project explores the development of a vision-based system for controlling a computer cursor using hand gestures. It leverages the power of Python libraries like OpenCV, Mediapipe, and PyAutoGUI to achieve real-time hand detection, gesture recognition, and corresponding cursor actions.

**Features**

Cursor Movement: Navigate the cursor on the screen using hand gestures.
Click Functions: Perform left, right, and double clicks with specific hand gestures.

**Requirements**

- Python 3.x
- OpenCV (pip install opencv-python)
- Mediapipe (pip install mediapipe)
- PyAutoGUI (pip install pyautogui)
- Webcam

**How it Works**

Capture Video: The system utilizes your webcam to capture video frames.
Hand Detection: Mediapipe's hand detection model identifies your hand in the frames.
Landmark Extraction: Key points on your hand (landmarks) are extracted for gesture recognition.
Gesture Recognition: The program analyzes the hand landmarks to determine the intended gesture (e.g., V-shape for cursor movement, extended middle finger for left click).
Cursor Control: Based on the recognized gesture, PyAutoGUI automates cursor movement or clicks.
Customization

The project offers flexibility for customization. You can potentially explore:

Adding new gestures for additional functionalities (e.g., scrolling, dragging).
Refining the gesture recognition logic for improved accuracy.
Incorporating error handling and user feedback mechanisms.
This project serves as a foundation for further development in hand gesture-based cursor control. Feel free to experiment and contribute to its evolution!

**Disclaimer**

This project is intended for educational purposes. The accuracy and performance of the gesture recognition system may vary depending on environmental factors (lighting, background) and individual hand postures.
