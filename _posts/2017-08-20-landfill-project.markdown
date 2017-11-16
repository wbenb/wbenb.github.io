---
layout: post
title: "The Denbigh Landfill Project  (Current)"
date: 2017-08-20 13:32:20 +0300
description: Currently working with the Newport News landfill to design prototype a remote monitoring system for the temperature of the compost piles. # Add post description (optional)
img: denbigh-landfill.jpg
tags:
---

## Objective
At the local science fair, we met a judge who worked for the local landfill. He was interested in designing a custom circuit that would monitor the temperature of their compost piles and log it remotely. This would eliminate the frequent labor and error associated with manually checking the temperature of the piles. I helped design and test the first-stage prototypes of this circuit.

## Parts
* Waterproof Electrical Enclosure
* PVC Pipe Screw-in Bulkhead Fitting
* Various PVC Pipe and Other Fittings
* Adafruit Feather Wifi Microprocessor
* Adafruit Featherwing SD Card Datalogger
* 4400 mAh Lithium Battery
* Waterproof OneWire Type Temperature Probes

## Details
The design needs to be low maintenance, waterproof, and durable. We housed the electronics in an waterproof electrical junction box with a clear top, and modified it to have a threaded water-tight PVC pipe connection at the bottom, where we attach a long PVC pipe 'probe'. For the first stages of prototypes, we wanted to log the data to a local SD, instead of sending over Wi-Fi, for easy troubleshooting. We wrote a simple program that takes the temperature from the sensor, writes it to the file on the SD Card, and tells the microprocessor to go into a 'deep sleep' mode for five minutes, at which time it wakes up and repeats the process. We told it to go into deep sleep so that it would use as little battery power as possible, so that we would almost never have to charge it. 

With the program written, we charged up the large Lithium Polymer battery and left the prototype to run sitting in our house, logging temperature every 5 minutes, until the battery dies. This first test was a success! The device logged data for 21 days straight, that equates to over 6,200 data points. At the end,  we just take the SD card out, plug it into a computer and graph the data in a spreadsheet.

## Next Steps
The next steps in this ongoing project are to package it up in its waterproof case, and place the probe in a mulch pile at the landfill for a real test. After this, I have looked into adding a solar based charging system that would make this setup fully self-sustained and never need to be charged. Once the landfill installs a WiFi system, I can enable the microprocessor's Wi-Fi capability and send the data up to the cloud to be stored and processed, instead of storing it on the SD card.
