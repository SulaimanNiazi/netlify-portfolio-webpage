---
type: ProjectLayout
title: Simple EEPROM Settings Manager
date: '2025-02-27'
client: Awesome client
description: >-
  Implementation of a simple non-volatile settings manager using EEPROM
  emulation in RAM. 
featuredImage:
  type: ImageBlock
  url: /images/Screenshot 2025-02-26 231125.png
  altText: Proteus Circuit
  caption: Proteus Circuit
  elementId: ''
addTitleSuffix: true
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg2.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 100
media:
  type: VideoBlock
  title: Proteus Simulation
  url: 'https://youtu.be/BD-YliszGkA'
  elementId: ''
  autoplay: false
  loop: false
  muted: false
  controls: true
  aspectRatio: '16:9'
---
## Project Overview

This project is a firmware embedded systems task's objective is to implement a simple non-volatile settings manager using EEPROM emulation in RAM. The project involves storing and retrieving configuration settings (e.g., brightness level), simulating power-off by clearing RAM, and ensuring settings persist after reset.

[Visit the Project](https://github.com/SulaimanNiazi/Simple-EEPROM-Settings-Manager)

[Download the Project](https://github.com/SulaimanNiazi/Simple-EEPROM-Settings-Manager/archive/refs/heads/main.zip)

## Table of Contents

1.  [Project Overview](#project-overview)

2.  [Skills Tested](#skills-tested)

3.  [Task Details](#task-details)

4.  [Apparatus](#Apparatus)

## Skills Tested

*   ✅ EEPROM-like data storage in RAM

*   ✅ Memory read/write operations

*   ✅ Use of MPLAB X Watch Window for testing

*   ✅ Basic error handling (corrupt data detection)

## Task Details

1.  **Create a configuration struct** to store user settings (brightness, mode).

2.  **Store settings** in EEPROM.

3.  **Allow modification of settings** and simulate power reset.

4.  **Verify settings** are restored correctly after simulated power-off.

## Apparatus

Necessary components that can't be changed:

1.  PIC16F877A microcontroller: To run the program.
2.  Quartz Crystal and 2 1nF non-polarized capacitors.

Optional components depending on your circuit:

1.  3 Buttons
2.  3 BCD 7-segment displays.
3.  3 Resistors.

