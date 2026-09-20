# Multidisciplinary-Design-Project

## Project Overview

This project was completed for **SC2079 Multidisciplinary Design Project** at **Nanyang Technological University** from **August 2024 to November 2024**.

The project involved developing an autonomous robotic system using an **STM32F407 microcontroller, Raspberry Pi, sensors, and computer vision**. The robot was designed to navigate a maze, recognise its surroundings, and perform automated parking.

## System Overview

The robotic system consisted of several integrated components:

* **STM32F407** – Low-level embedded control, motor control, sensor interfacing, and real-time task scheduling
* **Raspberry Pi** – Higher-level processing and communication with the STM32
* **Computer Vision** – Image recognition for identifying relevant visual information
* **Navigation Algorithm** – Maze-solving and navigation logic
* **Sensors and Motors** – Encoders, gyroscope, IR sensors, PWM-controlled motors, and PID-based motion control

The STM32 and Raspberry Pi communicated through **UART**, allowing the higher-level processing and navigation components to work together with the robot's low-level motor and sensor control.

## Features

* PID-based motor speed and motion control
* Encoder feedback for motor control and positioning
* Gyroscope and IR sensor integration
* UART communication between STM32 and Raspberry Pi
* PWM-based motor control
* FreeRTOS task scheduling
* Autonomous maze navigation
* Automated parking
* Integration with computer vision components

## Technologies

* **Microcontroller:** STM32F407
* **Programming:** C
* **RTOS:** FreeRTOS
* **Development:** STM32CubeIDE, STM32 HAL
* **Communication:** UART
* **Motor Control:** PWM, PID Control
* **Hardware:** Timers, Encoders, Gyroscope, IR Sensors
* **Processing:** Raspberry Pi
* **Computer Vision:** Image Recognition

## My Contributions

My primary focus was on the **STM32 embedded firmware and low-level robot control**.

* Developed embedded firmware for the **STM32F407** using C and STM32 HAL
* Implemented **PID-based motor and speed control**
* Integrated and tested **encoder feedback and sensor inputs**
* Configured and utilised **PWM, timers, and UART communication**
* Developed **FreeRTOS tasks** for concurrent motor control, sensing, and communication
* Worked on **STM32-Raspberry Pi communication and integration**
* Tested and debugged hardware-software integration
* Contributed to the integration and testing of the overall autonomous robot

## Other Team Components

The project was completed as a team, with different members responsible for different parts of the system.

* **Image Recognition:** Developed the computer vision and image-recognition components
* **Raspberry Pi:** Handled higher-level processing and communication with the STM32
* **Maze Navigation:** Developed the algorithms used for autonomous maze navigation
* **System Integration:** Combined the embedded control, Raspberry Pi, vision, navigation, and sensor components into the final robotic system

## Project Outcome

The completed system integrated **embedded control, sensor feedback, Raspberry Pi processing, computer vision, and navigation algorithms** into an autonomous robot capable of **maze navigation and automated parking**.
