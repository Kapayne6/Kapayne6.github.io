---
title: Individal Block Diagram
tags:
- tag1
- tag2
---

## Overview

The supplied block diagram below displays my systems current configuration. My role is to manage and translate thermistor values into high or low signals which I can transmit to another teammates PCB using an 8 pin connector. My board will be active when it recieves a high signal from Digital pin 2 on connector 2 which will then trigger thermistor values to be read and translated.

PCB Information:

* power levels (1.5 mA)
* sensor - 2 Thermistors
* Actuator - No actuation supplied on this PCB
* team connections - Recieves input value from team light sensor. After comparing two separate temperature readings will output signal to teammates to trigger motor actuation.
* Power source - 5V Regulator to system (9-12V can be supplied through barrel jack)
* ...


## Thermistor PCB Block Diagram

![Personal Block Diagram: ](Personal_Block_Diagram2.png)
