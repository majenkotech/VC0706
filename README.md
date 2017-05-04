Modified Adafruit VC0706 Camera Driver
======================================

This library has been stripped of all references to SoftwareSerial so that
people who don't want to use the camera on Software Serial don't have to include
all that extra code in their sketch. 

It was modified from the original Adafruit sources.

-----------

Original Adafruit README:
----


  This is a library for the Adafruit TTL JPEG Camera (VC0706 chipset)

  Pick one up today in the adafruit shop!
  ------> http://www.adafruit.com/products/397

  These displays use Serial to communicate, 2 pins are required to interface

  Adafruit invests time and resources providing this open source code, 
  please support Adafruit and open-source hardware by purchasing 
  products from Adafruit!

  Written by Limor Fried/Ladyada for Adafruit Industries.  
  BSD license, all text above must be included in any redistribution


To download. click the DOWNLOADS button in the top right corner, rename the uncompressed folder VC0706. Check that the VC0706 folder contains VC0706.cpp and VC0706.h

Place the VC0706 library folder your <arduinosketchfolder>/libraries/ folder. You may need to create the libraries subfolder if its your first library. Restart the IDE.
