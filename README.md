# HAB4.0Payload

This project is run annually by WPI students, each year's team making a payload to be flown attached to a helium balloon and base station to receive data from it during flight. The main purpose of this project is to monitor the presence of greenhouse gases, the ozone layer, and intensity of UV light, but also to safely retrieve the payload once the helium balloon pops mid-flight. My main task on the team was to develop the code for the payload, which consists of an Arduino, Raspberry Pi, and various sensors and modules.

Main Functionality:
1. Autonomous flight termination (programmable GPS boundary)
2. Radio transmission of sensor and image data during flight (credit to my colleague Nicholas Chantre for image transmission code)
3. Multithreading to prevent delays and hanging of core processes
3. Neat organization of sensor data into Excel compatible files

Sensors and Modules:
1. Altitude/Pressure Sensor (I2C) - https://www.sparkfun.com/products/12909
2. Temperature Sensor (Serial) - https://www.sparkfun.com/products/11050
3. Carbon Dioxide Sensor (Analog) - https://www.dfrobot.com/product-1023.html
4. Methane Sensor (Analog) - https://www.mouser.com/ProductDetail/474-SEN-09404
5. Ozone Sensor (I2C) - https://www.dfrobot.com/product-2005.html
6. UV Sensor (I2C) - https://www.sparkfun.com/products/15089
7. GPS (USB) - https://www.yic.com.tw/en/products-en/gps-gnss-antenna-modules/
8. Pi Camera - https://www.raspberrypi.com/products/camera-module-v2/
