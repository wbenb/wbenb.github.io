---
layout: post
title: "Laser Cutter Project"
date: 2017-07-24 13:32:20 +0300
description: Constructed and wired an 80 watt laser cutter for manufacturing robot parts.  # Add post description (optional)
img: laser-cutter-main.jpg # Add image post (optional)
tags: [Laser, Robotics]
---

## Purpose
During the robotics build season we only have 6 weeks to build the robot, so we dont have alot of time to design, prototype, and test parts of the robot. The team was offered the chance to buy a old laser cutter, missing some parts, from one of the mentor's coworkers. We decided that it would be very helpful to use the laser cutter to make prototype parts faster, and more accurately out of wood or plastics. Once we got the old laser cutter up and running with the old parts, we got all brand new parts to build a new one from scratch that is double the power, and double the size.

## Parts
* Custom Aluminum 80/20 Frame
* XLE X/Y Stage Frame
* 80 Watt Laser Tube
* 80 Watt Laser Power Supply
* Water Chiller Unit
* 2 Stepper Motors and Drivers with Encoders
* 2 48 Volt Power Supplies
* LightObject X7 Laser Controller
* 24 Volt Power Supply
* Custom Power Distribution Panel
* Air Pump

## Details
We started by building a large aluminum frame from 80/20 that can accomodate the 4 foot long laser tube and large cutting space. We then assembled the x and y frame from a kit, and upgraded to stepper motors with built in sensors for closed loop control. We mounnted all the electronics and made a custom control panel with the screen, usb port, current meter, emergency stop, and laser tube current meter. In order to power the air pump, water chiller, and 4 power supplies, I designed and built a custom power distribution board to get wall outlet voltage from the power entry module with circuit breaker to the unswitched and emergency switched circuits. This way when the emergency stop is activated, the motor movement is disabled, the laser is disabled, but the control system, air pump, and water chiller stay on. We then used the laser to cut and engrave many different types of materials, and record the power level and speed in a table for future use. Then, we can render a 2D drawing DXF file from a 3D CAD model, and put it on a USB stick then plug it into the laser cutter. The next steps in this porject are making the door used to acsess the table spring loaded so it can open and stay up while inserting or removing material, and also potentially build some kind of fume extraction system with a fan that can take smoke away from the workpiece and exhuast it outside the plastic encolure of the laser cutter.
