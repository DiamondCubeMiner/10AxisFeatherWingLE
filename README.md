# 10AxisFeatherWingLE #
A 10-DOF Featherwing, powered by LSM9DS1 and BMP280.

## Description ##
This featherwing uses I2C to connect both the IMU (LSM9DS1) and the altimeter (BMP280) to the Feather.
I made this to design projects that require a 10-DOF IMU in a tiny package where breakouts can affect the weight a lot and may not be a good option, such as a quadcopter, a model plane, or a model rocket.

## Drivers ##
These drivers should work as the project is a derivative of SparkFun hardware:
  - [SparkFun_LSM9DS1_Arduino_Library](https://github.com/sparkfun/SparkFun_LSM9DS1_Arduino_Library)
  - [SparkFun_BME280_Arduino_Library](https://github.com/sparkfun/SparkFun_BME280_Arduino_Library)

## Thanks ##
This project is derived from the following projects:
  - [SparkFun 9DoF Sensor Stick](https://github.com/sparkfun/9DOF_Sensor_Stick)
  - [SparkFun Atmospheric Sensor Breakout - BME280 (Qwiic)](https://github.com/sparkfun/Qwiic_Atmospheric_Sensor_Breakout_BME280)

Thanks to Sparkfun for their open-source schematics and libraries!

## License ##
This work is licensed under the Creative Commons Attribution-ShareAlike 4.0 International License. To view a copy of this license, visit http://creativecommons.org/licenses/by-sa/4.0/ or send a letter to Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.