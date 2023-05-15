# Smart_car_parking-Project

## Description :
Our project focuses on a smart car parking system that utilizes ultrasonic sensors to detect vehicles. When a car is detected, the sensor sends this data using Zigbee protocol to a coordinator, which displays the information on an LCD display. Additionally, the system uses smart LED indicators that glow red when a parking space is occupied and green when it is free. This innovative solution aims to streamline parking management, improve user experience, and optimize urban parking efficiency.

## Hardware :
1. Sensors              : Ultrasonic sensors
2. Controller/Modules   : ATmega16A, Xbee s2c wireless module with Antenna, XBee USB Adapter based on CP2102 IC
3. Display              : LCD display, LED's

## Software :
1. IDE                      : Microchip studio, Digi XCTU
2. Communication protocols  : MQTT, Zigbee 
3. IOT                      : AWS, Node-Red
4. Programming language     : Embedded-C

## Folder details:
1. LCD_DISPLAY : This folder contains lcd driver code and lcd application code for display. It also have .hex file which you can directly dump into microcontroller and
it will display information.
