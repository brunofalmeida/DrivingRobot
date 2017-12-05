# Driving Robot

An Arduino-powered driving robot that senses nearby objects and can be controlled by an Android device over Bluetooth.

Arduino: https://github.com/brunofalmeida/DrivingRobot-Arduino

Android: https://github.com/brunofalmeida/DrivingRobot-Android

<img src="Photos/12-04-Dec4-3.jpg" width="68%"> <img src="Photos/AndroidApplication.png" width="28.7%">


## Electrical Schematic

**Designed in KiCad**

![](CAD/Electrical/ElectricalSchematic-Colour-Cropped.png)


## 9V Battery Box

**Designed in SolidWorks**

**3D printed using MakerBot Print software and MakerBot Replicator 2 machine**

[Model](https://github.com/brunofalmeida/DrivingRobot/blob/master/CAD/Mechanical/9VBatteryHolder.STL)

![](CAD/Mechanical/9VBatteryHolder.png)


### Key Components

[Arduino Uno](https://www.creatroninc.com/product/arduino-uno-rev3/): Microcontroller

[HC-05](https://www.creatroninc.com/product/hc-05-bluetooth-module/): Bluetooth module

[HC-SR04](https://www.creatroninc.com/product/hc-sr04-ultrasonic-sensor/): Ultrasonic sensor
- Measures the distance to nearby objects using the time between when the wave is produced and when it returns

[SN754410](https://www.creatroninc.com/product/sn754410-quad-half-bridge-driver-36v-11a/): H-bridge to drive motors


## Photos

### May 9

- Bought components
- Assembled chassis, motors, wheels, and battery box

<img src="Photos/05-09-May9-1.jpg" width="49%"> <img src="Photos/05-09-May9-2.jpg" width="49%"> <img src="Photos/05-09-May9-3.jpg" width="49%">


### May 24

- Implemented basic motor control

<img src="Photos/05-24-May24.jpg" width="49%">


### July 7

- Implemented the Bluetooth module to receive driving commands
- Implemented the ultrasonic distance sensor to stop when in danger of hitting an object in front
- Added LEDs to indicate when a command has been received

<img src="Photos/07-07-July7-1.jpg" width="49%"> <img src="Photos/07-07-July7-2.jpg" width="49%"> <img src="Photos/07-07-July7-3.jpg" width="49%"> <img src="Photos/07-07-July7-4.jpg" width="49%">


### July 18

- Wiring tweaks
- Added a capacitor across the motor battery to reduce fluctuations

<img src="Photos/07-18-July18-1.jpg" width="49%"> <img src="Photos/07-18-July18-2.jpg" width="49%"> <img src="Photos/07-18-July18-3.jpg" width="49%"> <img src="Photos/07-18-July18-4.jpg" width="49%"> <img src="Photos/07-18-July18-5.jpg" width="49%">


### December 4

- Designed a custom 9V battery holder using SolidWorks
- 3D printed the 9V battery holder using MakerBot Print software and a MakerBot Replicator 2 machine

<img src="Photos/12-04-Dec4-1.jpg" width="49%"> <img src="Photos/12-04-Dec4-2.jpg" width="49%"> <img src="Photos/12-04-Dec4-3.jpg" width="49%">
