# Hexapod Robot

This project is a six-legged walking robot (hexapod) controlled by an Arduino and using the Adafruit PCA9685 PWM driver to control the servos.

## Hardware Requirements
- Arduino board (e.g., Arduino Uno)
- Adafruit PCA9685 PWM Servo Driver
- 12 x MG995 or MG996R servos
- Hexapod chassis

## Software Requirements
- Arduino IDE
- Adafruit PWM Servo Driver Library

## Circuit Diagram
Connect the servos to the PCA9685 board. Connect the PCA9685 to the Arduino using I2C (SDA to A4, SCL to A5 on Arduino Uno).

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/hexapod-robot.git
    ```
2. Open the `hexapod_robot.ino` file in the Arduino IDE.
3. Install the Adafruit PWM Servo Driver Library from the Library Manager.
4. Upload the code to your Arduino board.

## Basic Usage
The robot can perform basic movements like walking forward, backward, and turning. The key functions are:

- `GoHome()`: Move all legs to the initial home position.
- `walk_front()`: Make the robot walk forward.
- `walk_back()`: Make the robot walk backward.
- `turn_right()`: Make the robot turn right.
- `turn_left()`: Make the robot turn left.


## Side Note:
I wrote this file using the aide of AI:
- ChatGPT
- OpenAI
- [Website](https://www.openai.com)
