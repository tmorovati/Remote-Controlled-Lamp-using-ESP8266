# Remote-Controlled-Lamp-using-ESP8266

## Overview
This project involves creating a smart lamp that can be controlled remotely via a web server. The lamp utilizes an ESP8266 module for Wi-Fi connectivity and an AVR microcontroller, which is programmed using Arduino and CodeVision. The lamp can be turned on and off remotely through a user-friendly web interface.

## Components Required

- ESP8266 Wi-Fi module
- AVR microcontroller (e.g., ATmega series)
- Power supply for the lamp
- Lamp or light source
- Resistors, capacitors, and other necessary electronic components
- Arduino IDE
- CodeVision (for AVR programming)
  
## Project Setup
## Hardware Setup:

Connect the ESP8266 module to the microcontroller.
Connect the relay module to control the lamp.
Ensure all electrical connections are secure and accurate.

## Software Setup:

Install the Arduino IDE and ESP8266 board support.
Program the ESP8266 module to connect to your Wi-Fi network and set up a web server.
Program the AVR microcontroller to receive commands from the ESP8266 and control the relay module to turn the lamp on and off.
Host a web page on your web server to provide a user interface for controlling the lamp.
User Interface:

Users can access the lamp control interface by visiting the IP address of your web server.
The interface should have options for turning the lamp on and off.

## Testing:

Verify that the lamp can be controlled remotely using the web interface.
Ensure the ESP8266 is successfully communicating with the AVR microcontroller.
Usage
Power up your smart lamp and ensure the ESP8266 module is connected to your Wi-Fi network.

Open a web browser on any device (e.g., smartphone, computer) and enter the IP address of your web server.

The web interface should appear, allowing you to control the lamp. Click the corresponding buttons to turn the lamp on or off.

The AVR microcontroller receives the commands from the web server and controls the relay module, which, in turn, controls the lamp.

## Future Improvements
Enhance the web interface with additional features, such as brightness control or color selection for RGB lamps.
Implement security features like user authentication to control the lamp.
Add scheduling and automation capabilities for turning the lamp on or off at specific times.
