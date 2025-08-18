+++
title = "Paparazzo"
feature = "rpi-arduino-interaction.png"
+++
#### Abstract
This project aimes to automate the photo-documentation of the growth over time of suspended algae specimen cells in 24-well plates, while serving as an introduction lesson to realising electro-mechanical prototypes from scratch. The underlying objective was to explore the development and implementation of tools and devices that address daily work requirements and do not exist, yet. The project included a stepper motor driven system capable, designed to moving a camera system in two dimensions to document growth of set up specimen. Alongside the exploration of several kinds of hardware components, delving into software and application development was part of the knowledge gathering experience. Using a single-board-computer as operation interface, possibilities of setting up a graphical user interface upon a complete functional operating system opened up. This enables operating the device, and independently controlling the micro-controller that instructs the drivers which again operate the motors. The camera is directly attached to and controlled by the single-board-computer. This breaks the interaction between the the single-board-computer and the micro-controller down to "make a move" <-> "make a picture".

#### Operating System

+ Raspberry Pi OS 12 (bookworm)
+ Usergroups: dialout

#### Software

+ arduino-cli: <AccelStepper.h>, <RTClib.h>, <Wire.h>
+ python3.11: os, time, Tkinter, datetime, setuptools, pkg_resources, subprocess, threading, serial, picamera2
+ Paparazzo

#### Links
+ [Github Repository](https://github.com/florianfeigl/paparazzo/)
