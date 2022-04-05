# Breakout-Boards

## Introduction

This is my collection of various breakout boards that do one or more of the following:
  * expose a removable MCU board's pins for headers or soldering
  * make edge-pinned boards like Adafruit's ItsyBitsy adaptable to a protoboard
  * add an I2C Qwiic/STEMMA QY port
  * expose debug pins SWDIO and SWCLK (SAMD21/M0) and the option for a Segger J-Link connector.

## Directory

### ItsyBitsy 32u4 3 & 5V
  * exposes unique pins in (2) 0.3" 16-pin headers so that they can be plugged into a protoboard
  * Qwiic version adds a SMD pad for a 4-cond JST SH Qwiic/STEMMA QT connector and a cut/solder pad for selecting 3 or 5V Qwiic Vcc.
  * __Neither of these boards have been fabricated or tested yet.__
  * Errata:
    * It looks like the protoboard holes are too large so I'll be switching to a standard 16-pin header soon.
    * Label JP1: 3V,5V and G,3V

![IB Basic image](ItsyBitsy_Basic/ItsyBitsy_Basic-top-400.png) ![IB Qwiic Image](ItsyBitsy_Qwiic/ItsyBitsy_Qwiic-top-400.png)
