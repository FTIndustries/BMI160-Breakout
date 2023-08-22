[English](https://github.com/FTIndustries/BMI160-Breakout)
# FTIndustries BMI160 IMU breakout
![preview](https://github.com/FTIndustries/BMI160-Breakout/blob/main/3dpreview.png?raw=true)\
Bosch Sensortec사의 BMI160 6DoF IMU를 사용하는 보드입니다. Adafruit STEMMA QT / Sparkfun Qwiic 시스템을 지원합니다. 잘 알려진 브랜드 없는 보드들과 같은 폼팩터를 가지고 있으며, 핀아웃이 동일합니다. 하지만 PCB 공간 부족으로 인해 SPI 인터페이스와 3.3V LDO는 제공되지 않습니다. 5V가 아닌 3.3V 전원을 공급해주셔야 합니다. 높은 전압을 인가하면 보드가 손상될 수 있습니다.

## I2C address
이 모듈은 기본 I2C 주소로 0b1101001 (0x69) 를 사용합니다. 0b1101000 (0x68) 으로 주소를 바꾸려면 모듈 뒷면의 점퍼를 납땜하십시오.
![backside](https://github.com/FTIndustries/BMI160-Breakout/blob/main/pcbback.png?raw=true)