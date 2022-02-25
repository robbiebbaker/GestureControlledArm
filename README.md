# Robotic-Arm-Manipulation-using-OpenCV
A 3 D printed Robotic arm controlled by 6 servo motors for each finger of the arm and one to manage the wrist. As the user shows his hand gesture in front of the camera, OpenCV recognizes the gesture using contours and basic math to find out the number of fingers held up. Then OpenCV sends the information to Arduino Uno using serial communication. Arduino then sends commands to the servo motors and the respective fingers are shown.

Compents/Tools Required:
Arduino Uno,
webcam,
OpenCV-python,
5 servo motors,
connecting wires,
hand glove(optional)

## Robotic Arm Setup for Arduino

<p align="left">
  <img src="https://github.com/robbiebbaker/GestureControlledArm/blob/main/Serial%20Communication.jpeg" width=50% height=50%>
</p> 

## Image Processing with Open CV Process

<p align="left">
  <img src="https://github.com/robbiebbaker/GestureControlledArm/blob/main/Hand%20Gesture.png" width=50% height=50%>
</p> 

## CAD Drawings
The arm is split into 4 printable pieces and the fingers are each split into 3 joints similar to that of a human. 

<p align="left">
  <img src="https://github.com/robbiebbaker/GestureControlledArm/blob/main/CAD/Robotic%20Arm%20Design%20View%20%231.png" width=50% height=50%>
</p> 

<p align="middle">
  <img src="https://github.com/robbiebbaker/GestureControlledArm/blob/main/CAD/Robotic%20Arm%20Design%20View%20%232.png" width=50% height=50%>
</p> 

<p align="right">
  <img src="https://github.com/robbiebbaker/GestureControlledArm/blob/main/CAD/Thumb%20Design.png" width=50% height=50%>
</p> 

