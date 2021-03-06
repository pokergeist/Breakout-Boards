# Cirque Trackpoint FFC-12 to QT Py Adapter Board

The Cirque TM035035 is a capacitive touch sensor module, available in 23, 35, and 40mm diameters, with both SPI and I2C interfaces.

In the associated appication created by Ron Nelson (nelsonii), the Cirque trackpad was interfaced to an Adafruit QT Py microcontroller to create a capacitive touch joystick for use by Assistive Technology users.
My working title was "QT Stick" - hence the filenames. Ron will be using another name for his product, so the filenames will likely change.

This board was created to eliminate miniature point-to-point soldering for Assistive Technology Makers (ATMakers.org) by providing an FFC-12 socket on a board
supporting the soldering of Adafruit's 's castellated pins. The FFC-12 cable supports both I2C and SPI interfaces along with the trackpad's three "button" outputs B1-B3.

![Board Top](assets/QT%20Stick-top-400.png) ![Board Bottom](assets/QT%20Stick-bot-400.png)

## Directory Contents

__Board directories__ typically contain the following:
  * Eagle PCB .brd (board) and .sch (schematic) files.
  * all Gerber files for manufacturing in a zip file
  * The schematic rendered as PDF.
  * Renderings of the board, top and bottom, and maybe a photo of a populated board.