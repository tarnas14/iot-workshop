# Workshop:  IoT Experiments - build your own prototype!

## Description
This repository contains sources for IoT Experiments workshop.
The workshop is based on programming NodeMCU (ESP8266) with Arduino IDE.

Work is split to four parts (steps):
- device assembly
- work with temperature sensor
- HTTP calls
- connection to cloud - Yaas


## Requirements

### Install Arduino IDE
https://www.arduino.cc/en/Main/Software

### Add NodeMCU board

- run Arduino
- go to File > Preferences and "http://arduino.esp8266.com/staging/package_esp8266com_index.json" to Additional Board Manager URLs, save changes
- go to Tools > Board > Boards Manager, search for ESP8266, click on it and Install

### Add libraries

Go to Sketch > Include Library > Manage Libraries
Search and install:
 - Adafruit Unified Sensor based libraries
 - DHT sensor library
 - ArduinoJson

### Install USB drivers
 - OSX: [Install driver](tools/drivers/osx/osx-vcp-driver.zip)

### Install REST client for communication with cloud
We suggest to install Postman (from chrome web store). But you can use any other client you like and know how to use.
