# ros_plutarco
Group of ROS packages that implent the high level control framework of PlutarcoRobot

#Plutarco serial port setup
Plutarco Robot is equiped with a lot of serial device like IMU, Arduino, DataLogger, uNav etc...
this is actual port mapping:
* /dev/ttyUSB0 : uNav
* /dev/ttyUSB1 : IMU - Razor
* /dev/ttyUSB2 : GPS
* /dev/ttyACM0 : Touch controller of Manga LCD
* /dev/ttyACM1 is used by and Arduino board with rossserial protocol to perform a simple datalogger.
