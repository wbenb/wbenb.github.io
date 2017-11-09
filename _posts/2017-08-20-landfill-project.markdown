---
layout: post
title: "The Denbigh Landfill Project"
date: 2017-08-20 13:32:20 +0300
description: Working with the Newport News landfill to design prototype a remote monitoring system for the temperature of the compost piles. # Add post description (optional)
#img: denbigh-landfill.jpg # Add image post (optional)
tags:
---

## Objective
At the local science fair, we met a judge who worked for the local landfill, and he was interested in designing a custom circuit that would monitor the temperature of their compost piles and log it remotely to eliminate the labor and error ascociated with manually going and checking the temperature of the piles. I helped design and test the first-stage prototypes of this circuit.

## Parts
* Waterproof Electrical Enclosure
* PVC Pipe Screw-in Bulkhead Fitting
* Various PVC Pipe and Other Fittings
* Adafruit Feather Wifi Microprocessor
* Adafruit Featherwing SD Card Datalogger
* 4400 mAh Lithium Battery
* Waterproof OneWire Type Temperature Probes

## Details
The design needs to be able to be low maintenance, waterproof, and durable. We put the electronics in an waterproof electrical junction box with a clear top, and modified it to have a threaded water-tight PVC pipe connection at the bottom where we can attach a long PVC pipe 'probe'. In the first stages of prototypes we wanted to log the data to a local SD instead of sending over Wifi, for easy troubleshooting. We wrote a simple program that takes the temperature from the sensor, writes it to the file on the SD Card, and tells the microprocessor to go into a 'deep sleep' mode for the next five minutes, then wake up and repeat the process. We told it to go into deep sleep so that it would use as little battery power as possible, so that we would almost never have to charge it. 

With the program written, we charged up the large Lithium Polymer battery and left the prototype to run sitting in our house, logging temperature every 5 minutes, until the battery dies. This first test was a success! The device logged data for 21 days straight, that equates to over 6,200 data points. At the end we can just take the SD card out, plug it into a computer and graph the data in a spreadsheet.

## Next Steps
The next steps in this ongoing project are to package it up in its waterproof case, and put it out in the landfill for a real test. After this I have looked into adding a solar based charging system that would make this setup fully self-sustained and never need to be charged. Once the landfill has had a WiFi system installed, so I can enable the microprocessors wifi capability and send the data up to the cloud to be stored an processed instead of storing it on the SD card.
