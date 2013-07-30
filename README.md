DAS.UHR Schematics
==================

This repository contains the schematics and PCB design files for the DAS.UHR word clock.

These files have been created with the [EAGLE](http://www.cadsoftusa.com/) PCB software.

The PCB design meets the specifications of [OSH Park](http://oshpark.com/) community PCB order.


Bill Of Materials
-----------------

ICs
* **IC1** MCP1700 voltage regulator 3.3V 250mA TO-92-3 (Digi-Key MCP1700-3302E/TO-ND)
* **IC2** ATMEGA88PA 28-DIP (Digi-Key ATMEGA88PA-PU-ND)
* **IC3** 74HC4017 counter 16-DIP (Digi-Key 1026-M74HC4017B1R-CHP)
* **IC4-IC6** quad-MOSFET 14-DIP (Digi-Key TC4468CPD-ND)
* **IC7** PWM LED driver 28-DIP (Digi-Key 296-17732-5-ND)
* **IC8** DCF-77 receiver (Pollin 810 054)
* **IC9** real-time clock 8-DIP (Digi-Key DS1307+-ND)
* **CON2** serial Bluetooth transceiver module JY-MCU BT_BOARD V1.2

Capactitors
* **C1, C2** ceramic 1µF 50V (Digi-Key 490-5375-ND)
* **C3-C9** ceramic 100nF 50V (Digi-Key 490-3811-ND)
* **C10** electrolytic 100µF 10V (Digi-Key P5123-ND)

Resistors
* **R1, R4-R6** 10kΩ (Digi-Key 10KQBK-ND)
* **R2** 1kΩ (Digi-Key 1.0KQBK-ND)
* **R3** 330Ω (Digi-Key 330QBK-ND)
* **R7** trimmer 5kΩ (Digi-Key CT6EP502-ND)
* **R8+R9** 2.2kΩ (Digi-Key 2.2KQBK-ND)

Other
* **Q1** crystal 32.768 kHz 12.5pF (Digi-Key 300-8303-ND)
* **LED1** LED 3mm (Digi-Key 754-1211-ND)
* **T1** ambient light sensor (Digi-Key 751-1059-ND)
* micro-USB power supply 5V 500mA (Digi-Key 454-1496-ND)
* Nichia Superflux LED white 10lm 100° NSPWR70CSS (LUMITRONIX 11011)
* bluetooth module JY-MCU BT_BOARD 1.2 (eBay)

Sockets and Connectors
* **CON1** micro-USB A/B receptacle SMD 90° (Digi-Key H11635CT-ND)
* **CON2** female header 6-pos 2.54mm 90° (Digi-Key S5481-ND)
* **ISP1** header 6-pos 2.54mm (Digi-Key 609-3210-ND)
* **CON3, CON4** header 2.54mm 36-pos (Digi-Key S1011E-36-ND)
* **IC2, IC7** DIP socket 28-pos (Digi-Key A100210-ND)
* **IC3** DIP socket 16-pos (Digi-Key A100206-ND)
* **IC4-IC6** DIP socket 14-pos (Digi-Key A100205-ND)
* **IC8** female header 4-pos 2.54mm (Digi-Key S7037-ND)
* **IC9** DIP socket 8-pos (Digi-Key A100204-ND)
* female header 9-pos 2.54mm (Digi-Key S7042-ND)
* female header 11-pos 2.54mm (Digi-Key S7044-ND)


License
-------

Copyright 2012 Daniel A. Spilker

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
