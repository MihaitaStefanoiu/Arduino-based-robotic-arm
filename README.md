Smartphone-Controlled Robotic Arm

This project, developed by Luci-Mihăiță Ștefănoiu under the guidance of Dr. Ing. Mihnea Marin, presents a robotic arm controlled via a smartphone using Arduino technology. It serves as an accessible introduction to robotics, mechatronics, and Arduino programming, ideal for educational purposes, hobbyist demonstrations, and prototyping.

Overview

The robotic arm mimics human arm movements with six degrees of freedom (DOF), enabling complex and precise motions. It is controlled wirelessly through a smartphone application communicating via Bluetooth with an Arduino Uno, which processes commands to drive six HS-645MG servo motors. These motors manage the arm’s base rotation, shoulder, elbow, wrist tilt, wrist rotation, and gripper actions.

Components





Arduino Uno: Central control unit for processing smartphone commands.



Six HS-645MG Servo Motors: Facilitate arm movements and gripper control.



HC-05 Bluetooth Module: Enables wireless communication with the smartphone.



Breadboard: Provides flexible connections for components.



Battery: Ensures portability with independent power supply.



Smartphone with Arduino App: Sends control signals via sliders and buttons.

Functionality

The smartphone app allows users to control the arm’s movements through an intuitive interface with sliders for each servo motor. Commands are sent via Bluetooth to the Arduino, which translates them into precise motor actions. Users can save sequences of movements, execute them automatically, and adjust speed. A reset function clears stored sequences for reprogramming.

Applications





Education: Teaches robotics and Arduino programming principles.



Hobbyist Projects: Demonstrates technological capabilities at exhibitions.



Prototyping: Facilitates experimentation with robotic configurations.

Code

The Arduino code, utilizing SoftwareSerial and Servo libraries, manages Bluetooth communication and servo control. The setup() function initializes components, while loop() processes incoming commands. The runservo() function executes saved movement sequences, with pause and speed adjustments available.

Conclusion

This project showcases the versatility of Arduino in robotics, offering a cost-effective, open-source solution for learning and experimentation. The complete code and documentation are available in the repository, encouraging further exploration and customization.
