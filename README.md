# Sumo Robot based on Arduino Uno 

## Team members: Toktokozhoev Urmat, Akylbekova Rozalina

This project is dedicated to creating a Sumo Robot based on Arduino Uno. The robot can rotate in place, detect a target using an ultrasonic sensor, approach it, and lift it with a servo motor. The robot is designed for competitions and educational purposes.

---

## Features
- Rotates in place to scan for targets.
- Detects objects using an ultrasonic sensor.
- Autonomously approaches detected targets.
- Lifts the target using a servo motor.

---

## Components Used
1. **Microcontroller**: Arduino Uno
2. **Motor Driver**: MH Electronics Motor Shield
3. **Sensors**: Ultrasonic Sensor (e.g., HC-SR04)
4. **Actuators**:
   - Servo motor (for lifting objects)
   - 2 DC motors (for movement)
5. **Power Supply**:
   - 2 battery holders
   - 2 rechargeable batteries
6. **Structural Components**:
   - 3D-printed parts for the robot chassis and lifting mechanism
     
![5424649132456404260](https://github.com/user-attachments/assets/cbde526d-9e1a-4702-aded-cc28635f2ecf)

---

## Required Tools
- Soldering kit
- 3D printer
- Screwdrivers and assembly tools
- Arduino IDE (for programming the microcontroller)

---

## Setup Instructions
1. **Assembly**:
   - Attach the motors to the chassis.
   - Mount the wheels on the motors.
   - Install the servo motor into the lifting mechanism.
   - Attach the ultrasonic sensor to the front of the robot.
   - Assemble the 3D-printed parts for the chassis and lifting mechanism.

2. **Wiring**:
   - Connect the motors to the MH Electronics Motor Shield.
   - Mount the motor shield onto the Arduino Uno.
   - Connect the ultrasonic sensor to the digital pins of the Arduino:
     * VCC - Analog 2
     * Trig - Analog 3
     * Echo - Analog 4
     * GND - Analog 5
   - Attach the servo motor to the designated pin on the motor shield (Ser1).
     * GND - -
     * VCC - +
     * Control - S
   - Power the setup using the battery holders and batteries.

3. **Programming**:
   - Install Arduino IDE on your computer.
   - Use the provided code to program the Arduino Uno.
   - Upload the code to the Arduino using a USB cable.

---

## Code Overview
The Arduino code includes:
- **Motor Control**: Manages the robot's rotation and movement.
- **Sensor Reading**: Continuously monitors the ultrasonic sensor for objects.
- **Target Detection**: Processes sensor data to identify objects.
- **Lifting Mechanism**: Controls the servo motor to lift objects.

https://github.com/user-attachments/assets/86cc273c-2e37-4399-9878-4458638c6b32

https://github.com/user-attachments/assets/71bc8797-6574-4688-85c0-177bbe9350d9

https://github.com/user-attachments/assets/d2d400e4-88fd-4a65-92ab-2504d60bad63

---

## License
This project is open-source and available for educational and personal use.

---

## Conclusion

In this project, we built a robot that demonstrates the basic principles of working with Arduino and peripherals such as ultrasonic sensors and servo motors. We learned:

- How to construct mechanisms using 3D printing. The robot was assembled entirely without glue, using bolts for all connections.
- How to connect and program motors and sensors.
- How to develop algorithms for autonomous robot control.

This project helps develop skills in robotics, programming, and engineering design, and provides an excellent foundation for more complex projects.
