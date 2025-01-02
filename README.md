<!-- python packages needs to install

opencv-python, 
pycaw, 
pyautogui, 
autopy, 
mediapipe, 
numpy -->


HandOMotion: Virtual Mouse System
HandOMotion is an innovative virtual mouse system designed to enhance accessibility and provide a hands-free computing experience. By leveraging MediaPipe, OpenCV, and PyAutoGUI, this project enables users to control a computer using intuitive hand gestures detected through a camera.

Features
Hands-Free Cursor Control: Move the cursor using your hand gestures in real time.
Click Actions: Simulate mouse clicks using specific gestures.
Scrolling: Perform scroll actions with intuitive hand gestures.
Zooming and Volume Control: Additional gestures for zoom and volume adjustment.
Enhanced Accessibility: Enables computer control without the need for physical input devices.
Technologies Used
Python: Core programming language for the project.
MediaPipe: For detecting and tracking hand landmarks.
OpenCV: For processing video frames and gesture recognition.
PyAutoGUI: For simulating mouse and keyboard actions.
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/fromsaurav/HandOMotion.git
cd HandOMotion
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Run the project:

bash
Copy code
python handomotion.py
Hand Gestures
Palm: Moves the cursor.
Fist: Scrolls down.
Forefinger: Simulates a click.
Forefinger + Middle Finger: Scrolls up.
Zooming and Volume Control: Separate gestures that avoid interference with other commands.
How It Works
The camera captures real-time video.
MediaPipe detects hand landmarks.
Hand gestures are mapped to specific mouse and system actions using PyAutoGUI.
Actions are executed based on the recognized gesture.


Demonstration video will be provided soon......

Future Enhancements
Add support for multi-hand gestures.
Improve gesture recognition accuracy under low-light conditions.
Integrate voice commands for hybrid control.
Extend to additional accessibility use cases.
Contributing
Contributions are welcome! To get started:

Fork the repository.
Create a new branch:
bash
Copy code
git checkout -b feature-name
Make your changes and test them.
Commit your changes:
bash
Copy code
git commit -m "Add feature-name"
Push to your branch:
bash
Copy code
git push origin feature-name
Create a pull request.
License
This project is licensed under the MIT License.

Contact
For questions or feedback, reach out to:

Saurav Teli

LinkedIn - www.linkedin.com/in/saurav-teli-89a27a263

