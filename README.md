[한국어](https://github.com/FTIndustries/BMI160-Breakout/blob/main/readme-ko.md)
# FTIndustries BMI160 IMU breakout
![preview](https://github.com/FTIndustries/BMI160-Breakout/blob/main/3dpreview.png?raw=true)\
Sensor breakout using Bosch Sensortec's BMI160 6DoF IMU, supports Adafruit STEMMA QT / Sparkfun Qwiic system. It uses the same form factor with well-known unbranded boards and it is pin-to-pin compatible. but unlike them, it does not feature SPI interface and 3.3V LDO due to lack of PCB space. You should power this board 3.3V, not 5V. Higher voltages will damage the board.

## I2C address
the module uses I2C address 0b1101001 (0x69) by default. to change it to 0b1101000 (0x68), solder the jumper at the back side of the module.
![backside](https://github.com/FTIndustries/BMI160-Breakout/blob/main/pcbback.png?raw=true)