# Digital Clock using ATMEGA328

## Introduction

This is an user digital clock project developed from zero.The clock marks hours, minutes and seconds, using an ATMEGA328P microcontroller.
The clock starts marking time from 00:00, in the moment that it's powered. To adjust time until desired hour and minute you have to use the circuit push buttons (in the right side of microcontroller). We have two push buttons, one to increment hours and another one to increment minutes.

## Features

1. Displays Time in hours and Minutes.

2. Should not get reset when turned off.

3. Should be able to macth the timezones as required.

## 4W and 1H

**What** - A digital clock to see current time.

**Why** - To get to know about electric circuits better.

**When** - Whenever needed, one should be able to see the time.

**Where** - Wherever he is.

 --------------------------------------------------------------------------
 
 **How** - By using Atmega328 microcontroller and SimulIDE.
 
 ## SWOT ANALYSIS
**Strengths** 
- Real time time display.
- Able to Reset the time. 
- Can adjust hours and minutes according to ones needs.

**Weakness**
- Not able to Load Seconds.
- It's Very common.

**Opportunities**

- Can add Alarm
- Can add temperature sensor.

**Threats**
- Lack of technology.
- Can get broken easily.

## High Level Requirements
**ID** __________________ **Description** _____________________ **Category**

HLR_01 __________________ Adding Hours and Minutes ___________ Software

HLR_02 __________________ Understanding Atmega328 ___________________ Software


## Low Level Requirements
**ID** __________________________ **Description**

LLR_01 __________________________ Circuit Design

LLR_02 __________________________ Simulation

# Structural Diagram

![93801](https://raw.githubusercontent.com/sparikshit/M2-Embedded_DigitalClock/main/2_Architecture/Structural%20Diag.jpeg)

# Behaviour Diagram 

![31231](https://raw.githubusercontent.com/sparikshit/M2-Embedded_DigitalClock/main/2_Architecture/Behavioural%20Diag.png)

# Block Diagram

![23131](https://raw.githubusercontent.com/sparikshit/M2-Embedded_DigitalClock/main/2_Architecture/Block%20Diag.png)

# Simulation

![31112](https://raw.githubusercontent.com/sparikshit/M2-Embedded_DigitalClock/main/2_Architecture/Simulation.png)

# Bill Of Materials

Capacitor-22 : Capacitor 22 pF
Capacitor-23 : Capacitor 22 pF
Push-13 : Push   
Push-14 : Push   
Push-15 : Push   
Resistor-16 : Resistor 1 kΩ
Resistor-167 : Resistor 1 kΩ
Resistor-168 : Resistor 1 kΩ
Resistor-169 : Resistor 1 kΩ
Resistor-170 : Resistor 1 kΩ
Resistor-20 : Resistor 1 kΩ
Resistor-21 : Resistor 1 kΩ
Seven Segment-10 : Seven Segment   
Seven Segment-27 : Seven Segment   
Seven Segment-28 : Seven Segment   
Seven Segment-29 : Seven Segment   
atmega328-2 : atmega328   

