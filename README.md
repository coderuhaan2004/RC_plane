# RC_plane
'''Overview
Our team is trying to build a RC plane which is controlled by a sensor through Arduino microcontroller. The aerodynamic stability of the plane is handled by PID technique. However due to limited resources we were not able to test its stability. Majority of our work has been on creating the code for the plane and optimizing it for better performance.

Specifications
The devices used in the project are:
Arduino Microcontroller 
1. 4 Servo motors
2. A BLDC motor
3. Controlling sensor (model is not finalized)

2 Servo motors are connected to the wings as ailerons. 1 servo motor is connected to the rudder and the last motor to the tail. Servo motors are controlled by sensors and further by the microcontroller.

Problems faced while framing the project:
1. Finding the right library for the code so that a communication between the remote and the plane establishes.
2. We initially designed the model without PID technique but due to poor stability of the plane we had to establish PID technique.
'''
