Modbus TCP to Modbus RTU gateway

[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by-nc/4.0/)  

This is my Modbus TCP to Modbus RTU gateway written in Python.
I run it on a [BeagleBone Green](http://beagleboard.org/Green) equiped with a [Waveshare CAN RS485 Cape](www.waveshare.com/wiki/RS485_CAN_CAPE) to communicate with my centralized ventilation system.

I've only tested Modbus functions [01,02,03,04,06] so far because i don't need any other functions for my purpose.
Maybe the gateway need to be exteded to support other functions.
