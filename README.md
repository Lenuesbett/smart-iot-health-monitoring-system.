# smart-iot-health-monitoring-system.
Project Overview

The Smart IoT Health Monitoring System is an embedded system designed to monitor a patient's body temperature and provide alerts when abnormal conditions are detected. The system uses an ESP32 microcontroller to read temperature data from the LM35 temperature sensor and display the results on an LCD screen. If the temperature exceeds a preset threshold, a buzzer and LED are activated to alert the user. The system can also communicate data through wireless connectivity for remote monitoring.

This project demonstrates the application of Internet of Things (IoT) technology in healthcare monitoring systems. It helps in real-time monitoring and early detection of abnormal health conditions.

Objectives

The main objectives of this project are:

To design a smart health monitoring system using ESP32

To measure body temperature using the LM35 sensor

To display temperature readings on an LCD display

To activate an alarm using a buzzer and LED when temperature is high

To implement wireless communication for remote monitoring

Hardware Components

The following hardware components were used in this project:

ESP32 Development Board

LM35 Temperature Sensor

LCD Display

Buzzer

LED

Jumper Wires

Breadboard

Power Supply

Software Requirements

The system was developed using the following software tools:

Arduino IDE

ESP32 Board Libraries

Embedded C Programming

System Working Principle

The LM35 temperature sensor continuously measures the body temperature and sends an analog signal to the ESP32 microcontroller. The ESP32 processes the signal and converts it into temperature values in degrees Celsius.

The measured temperature is then displayed on the LCD screen. If the temperature exceeds the predefined safe level, the system activates the buzzer and LED to alert the user.

The system can also transmit data wirelessly, allowing monitoring through a connected device.

Circuit Description

The LM35 sensor is connected to one of the analog input pins of the ESP32. The LCD display is connected using appropriate communication pins to show the temperature readings. The buzzer and LED are connected to digital output pins and are triggered when the temperature exceeds the threshold value.

Features

Real-time temperature monitoring

LCD display for easy reading

Automatic alert system using buzzer and LED

Wireless communication capability

Low power consumption

Applications

This system can be used in several areas including:

Hospitals and clinics

Home healthcare monitoring

Elderly patient monitoring

Remote health monitoring systems

Future Improvements

The system can be improved by:

Adding heart rate sensors such as MAX30102

Integrating cloud-based data storage

Developing a mobile application for monitoring

Adding more health monitoring parameters

Author

Name: Lenues Kiprono
Institution: Taita Taveta National Polytechnic
Course: Diploma in Mechatronic Engineering
