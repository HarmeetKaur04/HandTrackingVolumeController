# Hand-Tracking Volume Control System

A gesture-based, contactless volume control system that utilizes computer vision and machine learning techniques to track hand movements in real-time and adjust system audio accordingly. The system leverages **OpenCV**, **MediaPipe**, and **Pycaw** to achieve accurate hand tracking and seamless user interaction with the audio settings. <br>

## Features
- **Real-time Hand Tracking:** Detects and tracks hand movements using MediaPipe’s powerful hand detection model. <br>
- **Gesture-based Volume Control:** Adjust the system’s audio volume by moving your hand. The distance between your thumb and index finger controls the volume level. <br>
- **Cross-platform Compatibility:** Works on Windows systems where `Pycaw` can access audio control. <br>
- **Contactless Interaction:** Provides a touch-free method for adjusting audio volume, useful in situations requiring hygiene or convenience. <br>

## Demo
Here’s a demo of the system in action: <br>
[https://www.linkedin.com/posts/harmeetkaur04_innovation-computervision-machinelearning-activity-7233705243224502273-7SIQ?utm_source=share&utm_medium=member_desktop] <br>

## How It Works
1. **Hand Detection:** The system captures video input from a webcam and uses **MediaPipe** to detect hand landmarks. <br>
2. **Distance Measurement:** It calculates the distance between the thumb and index finger to determine the volume level. <br>
3. **Volume Adjustment:** The calculated distance is mapped to system volume levels using **Pycaw**. <br>

## Installation

### Requirements
- Python 3.7+ <br>
- OpenCV <br>
- MediaPipe <br>
- Pycaw <br>

## Configuration
-You can adjust sensitivity or change hand gesture configurations in the script under the volume_control.py file. <br>
-Add custom hand gestures or modify the logic to suit your application. <br>

## Contributing
Contributions are welcome! Please submit a pull request or open an issue if you find a bug or have a suggestion. <br>

## License
This project is licensed under the MIT License - see the LICENSE file for details. <br>

### Acknowledgments
-OpenCV <br>
-MediaPipe <br>
-Pycaw <br>
