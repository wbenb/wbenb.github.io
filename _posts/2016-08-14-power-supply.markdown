---
layout: post
title: "DIY Workbench Power Supply"
date: 2016-08-14 13:32:20 +0300
description: Designed and built a device that connects to PC power supply to provide multiple voltages used for running electronics.  # Add post description (optional)
img: power-supply-main.jpg # Add image post (optional)
tags:
---

## Purpose
While working on electronics, there is a need to power many different devices, such as small microprocessors, battery chargers, motors. Most of the time, I need to make room on a power strip to plug in a bulky wall adapter for each device. However, some devices, such as motors, dont have an easy way to plug in a power supply. They require a separate power supply with bare wires going to the proper terminals. I realized that we had a spare power supply from an old computer around the house, so I designed and built a device that allows me to use the PC power supply to power many different devices with different power requirements for quick and easy testing.

## Parts
* Hammond Plastic Project Box
* Screw down type Banana plugs
* Light-up metal latching button
* Elecrical Terminal Bus Bars
* Standard Fuse Holders
* 4 Pin ATX Power Plug
* 6 Pin ATX Power Plug
* 24 Pin ATX Power Plug
* Various Crimp Terminals and Hardware

## Details
I wanted to make a simple self contained circuit that you can plug into any standard PC power supply that allows you to tap off of the 3 volts, 5 volts, and 12 volts that the power supply outputs. I wanted the device to be versatile while still providing ease of use, and more importantly short-circuit protection. I picked out a set of Banana plug style connectors for the outputs because they allow you to also insert bare copper wire and screw them down to clamp the wire in place. I also picked out a set of fuse holders that can hold fuses of different ratings, from .5 amps to 30 amps, depending on the size and power requirements of the project. As a result, the power supply can be used to power small 5 volt arduino microprocessors, 3.3 volts LED lights, and even power hungry electric motors in robotics applictaions.

![Inside of Power Supply](http://wbenb.github.io/assets/img/power-supply-inside.jpg)
