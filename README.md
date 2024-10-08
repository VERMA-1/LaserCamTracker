# LaserCamTracker

LaserTracker is a Python-based system for real-time laser point tracking using computer vision techniques and servo control. It detects and tracks a laser point within a video feed, adjusting the position of a camera mounted on servo motors to keep the laser centered on a detected circular reference point.

![Screenshot 2024-04-23 190904](https://github.com/VERMA-1/LaserCamTracker/assets/97395660/297d52ea-335a-46f5-b5d3-8281fdeb4966)



https://github.com/user-attachments/assets/578fca9d-9767-4588-8963-230601e2f1c4



# Features
+ Real-time laser point detection and tracking using a webcam
+  Utilizes a pan and tilt setup with mounted lasers for precise positioning
+ Suitable for security camera systems and experimental setups
+ Detects and tracks circular reference points, adjusting the laser position accordingly
  
# Requirements
- Python 3.x with OpenCV and NumPy
- Arduino IDE for servo control
- Compatible webcam, Arduino nano board, 2 axis pan and tilt setup with mounted lasers(green),7805,Sg90,adapter,DC Jack,Jumper wire,Mini BreadBoard

# Circuit Diagram

![Screenshot 2024-04-23 185409](https://github.com/VERMA-1/LaserCamTracker/assets/97395660/7408645b-3110-48aa-b055-c6da168dd5f6)

# Setup
- Install Python Dependencies:

  pip install opencv-python numpy pyserial

- Upload Arduino Sketch

- Connect your Arduino board to your computer.

- Open the Arduino IDE and upload the provided Arduino sketch (arduino_nano.ino) to your Arduino board.

- Connect your webcam to your computer and ensure it's recognized.

- Connect the pan and tilt setup with mounted lasers to your Arduino board.

- Run the Python script (Opencv_code.py) to start the tracking system:python Opencv_code.py

- Point the laser at the camera and observe how the system tracks the laser point by adjusting the pan and tilt
  
# Contributors
 - Pushpendra Verma
 - Vishal Yadav
 - Sandeep Yadav
 - Shobhit Singh
