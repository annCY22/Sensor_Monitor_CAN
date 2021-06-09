# Sensor Monitoring using CAN module
Arduino Uno is the central processing unit which process the data from sensors and takes necessary actions based on the processed data. The data from temperature and humidity sensor is displayed on the LCD screen and a fan will turn on when the temperature goes beyond certain value. If the temperature will not come down and goes beyond a critical value, a buzzer will turn on.
Temperature and humidity sensors at the transmitting side and LCD, fan and buzzer is used at the receiver side.CAN shields are used for CAN communication.Arduino Uno board is used as the main processing unit and Arduino nano board is used to collect and send sensor data. In this CAN bus, only one node is transmitting and the other node is receiving.

