# Assistant Driving Car System

## Project Overview

This project involves the creation of a versatile Line Follower Robot with integrated obstacle avoidance capabilities. The robot, controlled by an Arduino UNO, is designed to follow a black line while being able to navigate around obstacles using infrared sensors and an ultrasonic sensor.

## Components Required

- Solderless Breadboard
- 4-wheel Robot Car Kit
- Arduino UNO
- IR Sensor x 2
- L298 Motor Driver
- Mini Servo Motor SG90
- Ultrasonic Sensor Holder
- Ultrasonic Sensor HC-SR04
- 4Pcs Smart Robot Car Tyres Wheels
- Male to Female Jumper Wires
- Male to Male Jumper Wires
- Hard Jumper Wire
- On/Off Switch
- 18650 Battery Holder – 2 Cell
- 18650 Battery Cell 3.7V x 2

## Circuit Diagram

![Circuit Diagram](https://marobotic.com/wp-content/uploads/2023/10/Your-paragraph-text-33-1320x743.png)

According to the circuit schematic, the robot is powered by two 3.7-volt batteries connected in series, providing a total of 7.4 volts. The Arduino controls two infrared sensors for line following, an ultrasonic sensor for obstacle detection, and a mini servo motor. The L298 Motor Driver facilitates the control of two DC gear motors for both clockwise and counterclockwise rotations.

## How to Use

1. **Assemble the Robot:**
   - Follow the provided instructions to assemble the 4-wheel robot car kit.
   - Connect the various components as per the circuit diagram.

2. **Upload the Code:**
   - Use the Arduino IDE to upload the provided Arduino code (`Assistant Driving Car System`) to your Arduino UNO.

3. **Power On:**
   - Turn on the power switch to activate the robot.

4. **Observe Robot Behavior:**
   - Place the robot on a track with a black line and observe its ability to follow the line.
   - Introduce obstacles, and the robot should navigate around them using the ultrasonic sensor.

## Code Explanation

- The `Assistant Driving Car Systemo` file contains the Arduino code for this project.
- Comments within the code provide detailed explanations of each section.

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to modify and use the code and resources as per the terms of the license.

Happy robot building!
