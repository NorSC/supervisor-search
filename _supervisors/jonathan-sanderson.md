---
layout: supervisor
title: Jonathan Sanderson
available: true
available_msc: false
available_phd: false
email: jonathan.sanderson@northumbria.ac.uk
website: https://nustem.uk/connect
office_hours: >-
  Drop-in hours to discuss the project:


  * Monday 26th Sep 11:00–12:00, Ellison E block, third floor (come in via the Zone entrance on Northumberland Road, follow signs to Think Lab).

  * Thursday 29th Sep 11:15 to 12:15, CIS ground floor. Look for the cardboard puppet.
research_group: Digital Learning Laboratory
research_themes:
  - Internet of Things
  - Human-Computer Interaction
additional_keywords:
  - Digital Living
  - Social Computing
  - Technology-Enhanced Learning
  - Embedded Systems
  - User Centred Design
technologies_languages:
  - C++
  - Python
additional_details: >-
  **Additional themes & keywords**: microcontrollers, Arduino, Raspberry Pi, Pi
  Pico, MicroPython, physical computing, digital making, digital tinkering,
  family learning, education, informal learning, STEM education, computer
  science education, pedagogy.


  My research interests centre on informal learning in computer science. A live outreach/engagement project, [Connect](https://nustem.uk/connect/), involves late primary-aged children (approx. 9-11 years old) working alongside their parents/carers to build electromechanical puppets operated by a microcontroller. The controllers are networked and use IoT protocols to exchange simple 'mood' messages between puppets. The task, workshop activities, mechanical and coding components are all tailored with the aim of prompting exploratory, 'tinkering' behaviour and conversations amongst participants.


  ## Project idea – bringing smoothed servo movement to the MicroPython ecosystem


  A key component of the Connect system is a servo motor control system, which builds on established libraries to allow the programmer to articulate complex animation sequences with minimal code. The current library is written in C++ and targets the Arduino platform.


  The [Raspberry Pi Pico](https://www.raspberrypi.com/products/raspberry-pi-pico/) platform is rapidly growing in popularity, particularly with the MicroPython runtime. This project would therefore aim to port the existing C++/Arduino servo animation library to MicroPython/Pi Pico. Along the way, you might:


  * Assess, critique and reimagine design decisions made in the original (Arduino) implementation.

  * Design (and implement) a coherent Python API with similar objectives.

  * Write documentation and example code to support users.

  * Investigate packaging as a python module for straightforward distribution and use.


  If it's not already obvious, this is a programming project. There are some slightly gnarly corners to navigate, several digressions or extensions you might choose to pursue, and some simplifications which could be made if necessary. You'll also be working in the constrained environment of microcontrollers. Oh, and: playing with cute cardboard robots.


  ## Reading, Links, etc


  * Arduino [ServoEasing library](https://github.com/ArminJo/ServoEasing). Very comprehensive library, well documented and commented. Targets multiple Arduino hardware environments, which can make tracing the code a little complex.

  * [Easing functions cheat sheet](https://easings.net). Graphical representations of easing functions, with (TypeScript) code examples.

  * [Pimoroni Servo2040 library](https://github.com/pimoroni/pimoroni-pico/tree/main/micropython/modules/servo). Current state-of-the-art MicroPython servo implementation. See also the corresponding [MicroPython examples](https://github.com/pimoroni/pimoroni-pico/tree/main/micropython/examples/servo2040), including [this eased movement example](https://github.com/pimoroni/pimoroni-pico/blob/main/micropython/examples/servo2040/simple_easing.py). Note that this library is Pico-specific, when MicroPython itself is highly portable across platforms and architectures. You may wish to explore the implications of this.

  * [ConnectServo library](https://github.com/NUSTEM-UK/ConnectServo). My (hacky?) Arduino library which implements a subclass of ServoEasing with per-servo movement queues and servo-to-servo messaging. It's worth noting that ServoEasing (above) has recently added some similar functionality, which may present an alternative implementation model.

  * [Raspberry Pi Pico documentation](https://www.raspberrypi.com/documentation/microcontrollers/raspberry-pi-pico.html).
---
