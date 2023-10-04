# *Maze-solver* 
 -  This project features a maze-solving robot that employs an ultrasonic sensor for obstacle detection and an Adafruit Motor Shield to control two DC motors.
 -  The robot aims to navigate through a maze using the ultrasonic sensor's readings to make informed decisions on movement directions.
## *Introduction*
The maze-solving robot is designed to autonomously traverse a maze environment. It utilizes an ultrasonic sensor to detect obstacles in its path and an Adafruit Motor Shield to control the movement of two DC motors. The robot's movements are determined based on the readings from the ultrasonic sensor, allowing it to navigate through the maze efficiently.
## *Components*
- Ultrasonic Sensor: Used for obstacle detection and measuring distances from obstacles in front of the robot.
- Adafruit Motor Shield: Controls the movement of the robot by driving two DC motors based on sensor readings.
- DC Motors: Two DC motors are responsible for the robot's movement within the maze.
## *Setup*
- Hardware Connection:
  - Connect the ultrasonic sensor to the appropriate pins on the microcontroller.
  - Attach the DC motors to the Adafruit Motor Shield, ensuring proper wiring and connections.
- Software Setup:
  - Upload the provided firmware to the microcontroller, ensuring the correct pin assignments and configurations.
  - Verify that the necessary libraries for the ultrasonic sensor and Adafruit Motor Shield are installed.
## *Usage*
- Power on the maze-solving robot in a maze environment.
- The ultrasonic sensor will continuously measure distances to detect obstacles.
- Based on the sensor readings, the robot will make movement decisions to navigate through the maze.
- The robot will adjust its direction accordingly, using the DC motors controlled by the Adafruit Motor Shield.
- The robot will continue to traverse the maze until it reaches the end or finds a path to the goal.
