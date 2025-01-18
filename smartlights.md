---
title: Smart Lights System
description: Midterm project for TEJ3MR course
---

1. TOC
{:toc}


* * *

## The Idea
Many people are constantly trying to make “smart” home adjustments to make their appliances more efficient. A smart lighting system displays how logic gates can be applied to the real world and will demonstrate the overall engineering process needed for other advanced projects. 

## Sensors and Switches
Inputs:
- Light sensor/photoresistor
- Motion sensor/PIR
- Manual nightlight switch
- anual room light switch
- Nightlight sensor override
- Room light sensor override

Outputs:
Nightlight
Room light

## Functionality
The project will contain two main systems: the nightlight and the main room light. The system created for the nightlight will first check the photoresistor to determine if it detects light. It is then put through a not gate to reverse the effects; turning the output to true if it does not detect much light. This output is then put into an AND gate along with the motion sensor. If the output is true, it will check if the automated sensor override for the night light is on which will only output true if the overrides are off (due to the not gate connected to it). This output is then put in an OR gate with the manual switch which will determine if the night light is turned on with automation or without. Using a capacitor, the light can stay on for a little longer as many people use night lights as a convenience tool; usually only to walk to their bed at night. The regular room light has a similar system. The reversed photoresistor is inputted into an AND gate along with the room light override. It is then put together with the manual light switch. Depending on the specific inputs, the light will have a specific effect depending on the sensor, override and manual switch. 

Some may believe that two manual and override switches are unnecessary and that only one of each is needed. However, it generally makes more sense for both systems to have their specific manual switch and override switches. For example, if a person wants to have the night light automated for when they are walking to their bed at night but do not want the main light to blast them as soon as they walk in. Having two separate overrides and manual switches can allow this system to be better personalized to specific needs; thus, making it “smarter”. 
