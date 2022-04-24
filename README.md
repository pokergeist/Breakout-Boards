# Breakout-Boards

## Introduction

This is my collection of various breakout boards that do one or more of the following:
  * expose a removable MCU board's pins for headers or soldering
  * make edge-pinned boards like Adafruit's ItsyBitsy adaptable to a protoboard
  * add an I2C Qwiic/STEMMA QT port
  * expose debug pins SWDIO and SWCLK (SAMD21/M0) and the option for a Segger J-Link connector.

## Directory Contents

__Board directories__ typically contain the following:
  * Eagle PCB .brd (board) and .sch (schematic) files.
  * all Gerber files for manufacturing in a zip file
  * The schematic rendered as PDF.
  * Renderings of the board, top and bottom, and maybe a photo of a populated board.

### ItsyBitsy 32u4 3 & 5V
  * exposes unique pins in (2) 0.3" 16-pin headers so that they can be plugged into a protoboard
  * Qwiic version adds a SMD pad for a 4-cond JST SH Qwiic/STEMMA QT connector and a cut/solder pad for selecting 3 or 5V Qwiic Vcc.
  * The IB Qwiic board have been fabricated so I can soon mark it as Validated.
  * [IB Qwiic README](ItsyBitsy_Qwiic/README.md)
  * [IB Basic README](ItsyBitsy_Basic/README.md)
  * To Do:

### [Feather](Feather_J-Link_Qwiic/README.md) w/ J-Link & Qwiic
  * Fabricated and tested to some degree for different projects.

## Adapter Boards

### [Cirque Trackpoint](Adapter_Boards/Cirque_Trackpoint/README.md) FFC-12 to QT Py Adapter Board

The Cirque Trackpoint (e.g., model TM035035) is a circular capacitive touch sensor module available in different diameters supporting SPI and I2C MCU interfacing. In this instance, the board has solder pads for an Adafruit QT Py SAMD21 M0+ (#4600).
