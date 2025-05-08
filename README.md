[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/AlBFWSQg)
# a14g-final-submission

    * Team Number: 30
    * Team Name: T800
    * Team Members: Jinrong Liu & Gengzhi Zhu
    * Github Repository URL: https://github.com/ese5160/a14g-final-submission-s25-t30-t800
    * Description of test hardware: (development boards, sensors, actuators, laptop + OS, etc), SAMW25 MCU, SCD30 CO2 Senor.

## 1. Video Presentation


## 2. Project Summary
### Device Description
The Smart Greenhouse System is an IoT-enabled environmental control platform that monitors and regulates temperature, humidity, CO₂ levels, and soil moisture to optimize plant growth. It automates irrigation based on real-time sensor data and remote cloud inputs.  

Inspired by the challenges of sustainable agriculture and urban farming, this project aims to solve the problem of manual greenhouse management by introducing autonomous, data-driven decision-making to reduce human effort and improve crop health.  

Our device uses Wi-Fi (via the SAMW25 MCU) to connect to the cloud through MQTT. This enables real-time remote monitoring and control from a Node-RED dashboard, allowing users to view live sensor data and toggle actuators such as LEDs and water pumps over the internet.  

### Device Functionality
This system integrates the following components:  

Sensors:  

SHT31: for temperature  

SCD30: for CO₂ concentration  and humidity  


Actuators:  

IRLZ34N MOSFET: controls water valve for irrigation  

On-board LED: for status/debug indication  

FIT0563 Water Pump  

Connectivity:  

SAMW25 MCU with integrated Wi-Fi  

MQTT protocol for bidirectional communication  

Node-RED dashboard for UI  

Subscribe MQTT node of SCD30 Sensor data upload, FIT0563 Water Pump control, and CLI command  

## 3. Hardware & Software Requirements

## 4. Project Photos & Screenshots
Final project:  
![Final project](https://github.com/ese5160/a14g-final-submission-s25-t30-t800/blob/main/images/finalproject.jpg)

PCBA top view:  
![PCBA top view](https://github.com/ese5160/a14g-final-submission-s25-t30-t800/blob/main/images/pcb_top.jfif)

PCBA bottom view:  
![PCBA bottom view](https://github.com/ese5160/a14g-final-submission-s25-t30-t800/blob/main/images/pcb_button.jfif)

Thermal camera image:  
![Thermal camera image](https://github.com/ese5160/a14g-final-submission-s25-t30-t800/blob/main/images/thermal.jfif)

2D Board design top view:  
![2D Board design top view](https://github.com/ese5160/a14g-final-submission-s25-t30-t800/blob/main/images/pcb2d_front.png)

2D Board design bottom view:  
![2D Board design bottom view](https://github.com/ese5160/a14g-final-submission-s25-t30-t800/blob/main/images/pcb2d_back.png)

3D Board design top view:  
![3D Board design top view](https://github.com/ese5160/a14g-final-submission-s25-t30-t800/blob/main/images/pcb3d_front.png)

3D Board design bottom view:  
![3D Board design bottom view](https://github.com/ese5160/a14g-final-submission-s25-t30-t800/blob/main/images/pcb3d_back.png)

Node-RED dashboard:  
![Node-RED dashboard](https://github.com/ese5160/a14g-final-submission-s25-t30-t800/blob/main/images/nodered_dashold.png)

Node-RED backend:  
![Node-RED backend](https://github.com/ese5160/a14g-final-submission-s25-t30-t800/blob/main/images/nodered_backend.png)

System block diagram:  
![System block diagram](https://github.com/ese5160/a14g-final-submission-s25-t30-t800/blob/main/images/detail%20block%20diagram.png)


## Codebase

[Link to final embedded C firmware codebases](https://github.com/ese5160/final-project-t30-t800)  
[Link to Node-RED dashboard code](https://github.com/ese5160/final-project-t30-t800/tree/main/Node-RED)


