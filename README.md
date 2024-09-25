Virtual Paint Application using Hand Gestures 🎨✋
This is a Python-based virtual paint application that utilizes OpenCV, Mediapipe, and a webcam to allow users to draw on a virtual canvas using hand gestures. The application detects hand landmarks in real-time and enables users to choose different colors or clear the canvas through gestures.

🚀 Features
Draw on a virtual canvas using hand gestures.
Choose different colors: Blue, Green, Red, and Yellow.
Clear the canvas with a specific gesture.
Real-time hand landmark detection using MediaPipe.
Dynamic drawing experience with multiple color points handling.
🛠️ Technologies Used
Python: Core language for development
OpenCV: For computer vision tasks such as accessing the webcam and image processing
Mediapipe: For real-time hand landmark detection
NumPy: For handling matrix operations and kernel creation
Deque from the collections module: To manage the drawing points of different colors
🖥️ How It Works
The webcam captures frames in real-time.
MediaPipe's hand detection model identifies the hand landmarks.
The user can draw on the canvas by moving their forefinger.
The application supports multiple colors and can switch between them using the thumb-to-finger distance.
Clearing the canvas can be done by selecting the "CLEAR" button.
🧰 Setup and Installation
Clone the repository:

bash
Copy code
git clone (https://github.com/NiteshAnand190/Hand-detection-canvas-drawing.git)
cd virtual-paint-gesture
Install the required packages:

bash
Copy code
pip install opencv-python mediapipe numpy
Run the application:

bash
Copy code
python virtual_paint.py
🕹️ How to Use
Color Selection:

Use your finger to hover over the color buttons displayed on the screen (BLUE, GREEN, RED, YELLOW).
The currently selected color will be used for drawing.
Drawing:

Draw on the screen using your index finger.
Move your hand to create lines in the selected color.
Clear the Canvas:

Hover your finger over the "CLEAR" button at the top of the screen to reset the canvas.
Quit the Application:

Press the q key on your keyboard to exit.
📸 Application Interface
The application has two windows:

Output: Displays the live video feed with your drawing on it.
Paint: Displays the virtual canvas where the drawing happens.
💡 Future Improvements
Adding more colors or custom color options.
Implementing different brush sizes.
Saving the drawing to a file.
Enabling eraser functionality.
📄 License
This project is licensed under the MIT License. Feel free to use, modify, and distribute it as needed.

🤝 Contributing
Contributions are welcome! If you have any ideas or improvements, feel free to create an issue or submit a pull request.
