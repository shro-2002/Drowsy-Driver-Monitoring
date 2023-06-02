# Drowsy Driver Monitoring and Detection
The Drowsy Driver Monitoring and Detection system is designed to prevent accidents caused by drowsy driving. It utilizes the combination of tkinter and OpenCV libraries to monitor the driver's behavior and activate an alert system when signs of drowsiness are detected.

## Components
The following are the key components of the project:

- CustomBlinkCascade.xml: Custom XML file containing the cascade for blink detection.
- Drowsiness Detection 2.ipynb: Jupyter Notebook file containing the code for drowsiness detection.
- README.md: Markdown file providing information about the project.
- beep-07.wav: Audio file containing the sound for the alert system.
- demo.png: Image file showing a demo of the GUI.
- haarcascade_eye.xml: XML file containing the cascade for eye detection.
- haarcascade_eye_tree_eyeglasses.xml: XML file containing the cascade for eye and eyeglasses detection.
- lbpcascade_frontalface.xml: XML file containing the cascade for frontal face detection.
## Features
- Head Inclination Detection: The system detects the driver's head inclination and monitors for any significant angle changes.
- Eye Level Shift Detection: It also tracks the driver's eye level and identifies any shifts that may indicate drowsiness.
- Alert System: When signs of drowsiness are detected, an alert mechanism is activated to help the driver stay alert and avoid accidents.
- Beeping Mechanism: The alert system includes a beeping sound to further assist the driver in staying awake and focused.

# GUI Using Tkinter
The system incorporates a Graphical User Interface (GUI) developed using the Tkinter library. The GUI provides a user-friendly interface to display the monitoring status, alert notifications, and other relevant information.

Setup and Usage
To use the Drowsy Driver Monitoring and Detection system, follow these steps:

Install the required libraries: Ensure that you have tkinter and OpenCV libraries installed on your system.
Run the application: Execute the Drowsiness Detection 2.ipynb notebook file to start the monitoring and detection system.
Monitor the driver: The system will use the webcam to track the driver's head inclination and eye level.
Alert System: When signs of drowsiness are detected, the alert system will be activated, including the beeping mechanism, to alert the driver and promote alertness.
Future Enhancements
The current version of the Drowsy Driver Monitoring and Detection system provides a basic set of features. Here are some potential future enhancements:

Eye Blink Detection: Incorporate eye blink detection algorithms to further enhance the drowsiness detection accuracy.
Facial Expression Analysis: Analyze facial expressions to detect signs of fatigue or drowsiness.
Machine Learning Integration: Utilize machine learning techniques to improve the system's detection capabilities and reduce false positives/negatives.
Real-time Monitoring: Enable real-time monitoring of the driver's behavior and provide instant feedback for enhanced safety.

# License
This project is licensed under the MIT License.

# Acknowledgments
The Drowsy Driver Monitoring and Detection system utilizes the tkinter and OpenCV libraries.
We acknowledge the contributions of the open-source community in providing valuable resources and inspiration for this project.
Please feel free to contribute to the project by submitting bug reports, feature requests, or pull requests.
