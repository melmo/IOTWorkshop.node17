## Contents

+ [Setting up a cloud environment](#setting-up-a-cloud-environment).
+ [Setting things up locally](#setting-things-up-locally).
+ [Setting it up on a pi](#setting-it-up-on-a-pi).
+ [The Wemos D1 Mini and the Arduino IDE](#the-wemos-d1-mini-and-the-arduino-ide).
+ [Tying it together](#tying-it-together).
+ [Integrating with vvvv](#integrating-with-vvvv).
+ [Integrating with vvvv](#integrating-with-nodejs).
+ [Integrating with NodeJS](#integrating-with-nodejs).
+ [Integrating with NodeJS](#some-stuff-for-later).

## [](#setting-up-a-cloud-environment)Setting up a cloud environment [(slides)](docs\slides\001-cloudEnviroment\index.html)
+ Basic setup
  + Creating an Ubuntu instance
  + Setting up port permissions
  + getting a static IP
  + sshing in
+ Adding Mosquitto
+ Adding node-red
  + Simple setup
  + Securing it (vital)

## [](#setting-things-up-locally)Setting things up locally
+ Setting up a broker locally
  + Mosquitto on windows
  + Mosquitto on good operating systems
+ Setting up node-red locally

## [](#setting-it-up-on-a-pi)Setting it up on a pi

## [](#the-wemos-d1-mini-and-the-arduino-ide)The Wemos D1 Mini and the Arduino IDE
+ Setup
  + Adding the board to the board manager
  + Settings
  + Pushing your first sketch - Blinking the LED
+ Using the ESP with other things
  + Button Shield
  + WS2812B RGB Shield
  + Motor Shield
  + Ultrasonic Distance
  + OLED
  + Analog Sensors
    + Photo resistor (LDR)
    + IR Reflectance

+ MQTT on the esp8266

## [](#tying-it-together)Tying it together
+ Simple UIs in node-red
+ node-red to the esp8266
+ and back
+ building some logic

## [](#integrating-with-vvvv) Integrating with vvvv
+ MQTT in vvvv

## [](#some-stuff-for-nodejs)Integrating with NodeJS
+  

## [](#some-stuff-for-later)Some stuff for later
+ Atom & PlatformIO
+ Homie



<!---

Homie
https://git.io/homieiot
https://github.com/marvinroger/homie/tree/master

homie for node-red
https://github.com/marvinroger/node-red-contrib-homie

homie for esp8266
http://marvinroger.github.io/homie-esp8266/
http://marvinroger.github.io/homie-esp8266/stable/

esp8266 file system
http://esp8266.github.io/Arduino/versions/2.3.0/doc/filesystem.html#uploading-files-to-file-system
http://docs.platformio.org/en/latest/platforms/espressif8266.html#uploading-files-to-file-system-spiffs

# Wemos
motor https://github.com/wemos/WEMOS_Motor_Shield_Arduino_Library

# Services

-->
