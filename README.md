# motor-speed-control

---

## 🚀 Motor Speed Control System using STM32

This project presents a **Motor Speed Control System** developed using the **STM32F446RE microcontroller**, designed to demonstrate real-time control of motor speed based on sensor inputs and user interaction. The system integrates multiple components such as a potentiometer, ultrasonic sensor, temperature sensor (DHT11), and servo motor to create an intelligent and responsive control mechanism.

The primary objective of the project is to control the motor (servo) speed and position dynamically under two operating modes: **AUTO mode** and **MANUAL mode**. In AUTO mode, the system adjusts the motor behavior based on environmental conditions. The ultrasonic sensor detects object proximity, and if an object is detected within a predefined threshold distance, the motor immediately shifts to a safe mid-position, ensuring collision avoidance. Additionally, temperature and light intensity inputs influence the motor’s operation, making the system adaptive to surrounding conditions.

In MANUAL mode, the motor speed and position are controlled using a potentiometer, allowing direct user input. However, even in manual mode, safety is prioritized—if the ultrasonic sensor detects a nearby obstacle, it overrides user input and forces the motor to a predefined safe position.

The project is implemented using **STM32CubeIDE and HAL libraries**, ensuring efficient peripheral configuration and modular code structure. Key features include PWM-based motor control, ADC-based analog input reading, real-time distance measurement using ultrasonic sensing, and UART communication for debugging and monitoring.

This system demonstrates practical concepts of embedded systems such as sensor integration, priority-based control logic, and real-time decision making. It serves as an excellent foundation for applications in robotics, automation, and smart control systems.

---
