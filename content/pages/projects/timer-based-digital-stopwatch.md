---
type: ProjectLayout
title: Timer Based Digital Stopwatch
date: '2025-02-26'
client: Mira Elektronikentwicklung
description: >-
  Digital stopwatch using Timer1. Displays elapsed time over UART in the format
  MM:SS:MS.
featuredImage:
  type: ImageBlock
  url: /images/Screenshot 2025-02-26 230902.png
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

This project implements a digital stopwatch using the PIC12F1572 microcontroller. The stopwatch uses Timer1 to count milliseconds and displays the elapsed time over UART in the format MM:SS:MS. The project is evaluated using software simulation in MPLAB X IDE.

[Visit the Project](https://github.com/SulaimanNiazi/Timer-Based-Digital-Stopwatch)

[Download the Project](https://github.com/SulaimanNiazi/Timer-Based-Digital-Stopwatch/archive/refs/heads/main.zip)

## Objective

- Implement a digital stopwatch using Timer1.
- Display elapsed time over UART in the format MM:SS:MS.
- Use software simulation in MPLAB X IDE to evaluate functionality.

## Skills Tested

- ✅ Timer configuration (1ms resolution)
- ✅ UART data formatting (Sending real-time updates)
- ✅ Interrupt handling
- ✅ Software simulation debugging

## Task Details

1. Use Timer1 to count milliseconds.
2. Convert time to Minutes:Seconds:Milliseconds (MM:SS:MS) format.
3. Send the formatted time over UART every second.
4. Use a software breakpoint in MPLAB X to verify correct time updates.