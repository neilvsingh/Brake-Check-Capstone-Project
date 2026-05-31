# Brake-Check-Capstone-Project (In Progress)
# Car Error Decoder and Vehicle Diagnostics Display

This project is an in-vehicle car error decoder designed to read vehicle diagnostic data and display useful information to the driver through a small screen and button-based interface. The goal of the system is to create a compact device that can communicate with a vehicle through the OBD-II port, decode error codes, and present warning messages in an easy-to-understand format.

The device concept uses an OBD-II communication module to receive diagnostic trouble codes and live vehicle data from the car’s onboard computer. This data can include engine fault codes, throttle position, brake pressure, temperature readings, and other sensor values depending on vehicle compatibility. A microcontroller processes the incoming data and controls the display, buttons, and warning system.

The software is designed to translate raw OBD-II codes into readable explanations, allowing the user to understand possible vehicle issues without needing a separate scanner. The interface uses physical buttons instead of a touchscreen so the device can remain simple, durable, and easy to operate.

Although there are other OBD-II decoders on the market, this project stands out as it is a user-friendly system that will also include a first of its kind AI-based wear prediction concept, where diagnostic codes and sensor trends could be analyzed to estimate potential vehicle wear or maintenance needs; preventing a breakdown before it even happens, saving drivers their time and money. This project demonstrates how embedded systems, vehicle communication, and data processing can be combined to create a practical automotive diagnostic tool.
