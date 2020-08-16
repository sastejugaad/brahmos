# BraHmos



[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

3D printed Model of fastest supersonic cruise missile in the world BraHmos. The BrahMos is a medium-range ramjet supersonic cruise missile that can be launched from submarine, ships, aircraft, or land. It is the fastest supersonic cruise missile in the world. It is a joint venture between the Russian Federation's NPO Mashinostroyeniya and India's Defence Research and Development Organisation (DRDO), who together have formed BrahMos Aerospace.

  - Type some Markdown on the left
  - See HTML in the right
  - Magic

# How to Build ths project

  1. Download Stl files.
2. Print the stl files using 3d printer. (No need for support Layer height 0.3mm)
3. Electronics used
   Node MCU
   MPU 6050
   o-led Screen
   2 x Servo
   Step Down converter 
   9v battery(optional)
4. step down converter is only neccesary if you are using 9v battery.If you are powering using USB then no need.
5. Install Node MCU Servo and MPU6050 library.
6. Upload the code


> Ciruit diagram is in the code folder.

# Installation
Before uploading the code switch node32s in the boards menu. By default node mcu is not installed.
Follow these steps to enalble node mcu option.
https://www.instructables.com/id/Steps-to-Setup-Arduino-IDE-for-NODEMCU-ESP8266-WiF/


#### You need to install following libraries for running the code.

<Adafruit_MPU6050.h>
<Adafruit_Sensor.h>
<Wire.h>
<ESP32Servo.h>
<Adafruit_GFX.h>
<Adafruit_SSD1306.h>

### Help
Code is pretty simple I have just used the default example provided by mpu6050 library and mapped the output to servo motors.thats it.

You can see the tutorial on youtube.
https://www.youtube.com/channel/UCe5G9yS2XvetGfjfT-O89vw?view_as=subscriber

For help Join discord
https://discord.gg/fMXvGty

