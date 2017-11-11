# Calaos Thermostat HAT

## About this project
This project is intended to provide hardware materials and calaos configuration to build a Thermostat for Raspberrypi.

The hardware part is a basic Raspberry B+ HAT and contains
* 1 relay
* Support for 1wire DS18B20 + available One wire port to add more sensors
* Teleinfo serial line

This project is perfect to control a Gaz heating system. The relay can activate/deactivate the heating system. The 1Wire bus can be used to connect a Temperature sensor. The teleinfo serial line, is specific to Enedis (ex ERDF) power meters.


## Content
* hardware : this directory contains the schematics and board layout of the HAT
* calaos_conf : this directory contains the additionnal configuration to add to
  your calaos setup in order to use the thermostat extension

