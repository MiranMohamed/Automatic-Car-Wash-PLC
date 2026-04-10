# Automatic Car Wash PLC System

## Project Description
This project implements an automatic car washing system using PLC programming in CODESYS.  
It is developed using both Ladder Diagram (LD) and Function Block Diagram (FBD).

The system simulates an automated car wash process where a vehicle moves through multiple stages controlled by sensors and timers.

---

## System Workflow

The process operates in the following sequence:

1. The entry sensor detects the car and activates the conveyor belt.
2. Stage 1: Soapy water is applied for 20 seconds when Sensor 1 is triggered.
3. Stage 2: Brushing process runs for 20 seconds when Sensor 2 is triggered.
4. Stage 3: Clean water is applied for 20 seconds when Sensor 3 is triggered.
5. Stage 4: Drying process runs for 60 seconds when Sensor 4 is triggered.
6. The exit sensor stops the conveyor belt when the car leaves the system.

---

## Demo Videos

LD Implementation: https://drive.google.com/file/d/1Jac-lF97XSXFq4t_rd7PC_RmE06XZyw3/view?usp=drive_link

FBD Implementation: https://drive.google.com/file/d/1m-x9_R2Q6uec1fhaeDXe970FfB3YsXis/view?usp=drive_link
