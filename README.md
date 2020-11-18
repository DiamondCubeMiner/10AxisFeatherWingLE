# 10AxisFeatherWingLE #
A 10-DOF Featherwing, powered by LSM9DS1 and BMP280.

## Description ##
This featherwing uses I2C to connect both the IMU (LSM9DS1) and the altimeter (BMP280) to the Feather.
I made this to design projects that require a 10-DOF IMU in a tiny package where breakouts can affect the weight a lot and may not be a good option, such as a quadcopter, a model plane, or a model rocket.

## Drivers ##

  - [Adafruit_LSM9DS1](https://github.com/adafruit/Adafruit_LSM9DS1/)
  - [Adafruit_BMP280_Library](https://github.com/adafruit/Adafruit_BMP280_Library/)

## Thanks ##
This project is derived from the following projects:
  - [Adafruit-ADXL343-ADT7410-Featherwing-PCB](https://github.com/adafruit/Adafruit-ADXL343-ADT7410-Featherwing-PCB)
  - [Adafruit-LSM9DS1-Breakout-PCB](https://github.com/adafruit/Adafruit-LSM9DS1-Breakout-PCB)
  - [Adafruit-BMP280-Breakout-PCB](https://github.com/adafruit/Adafruit-BMP280-Breakout-PCB)

## License ##
This work is licensed under the Creative Commons Attribution-ShareAlike 4.0 International License. To view a copy of this license, visit http://creativecommons.org/licenses/by-sa/4.0/ or send a letter to Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.