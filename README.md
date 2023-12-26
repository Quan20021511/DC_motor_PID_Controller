# Motor Speed PID Control

![machThiCong](https://github.com/Quan20021511/TT_XL_ANH/assets/129273695/89db84ce-c554-4b27-89e0-f5b6d3b597fa)

## Overview

This Arduino-based project implements a PID (Proportional-Integral-Derivative) controller for precise regulation of motor speed. The system utilizes a potentiometer for user-defined setpoints, an encoder for closed-loop feedback, and an LCD for real-time display. It is designed for applications that demand dynamic and accurate RPM control.

## Table of Contents

- [Features](#features)
- [Setup and Usage](#setup-and-usage)
- [Configuration](#configuration)
- [Contributions](#contributions)

## Features

- **PID Control:** Dynamic adjustment of motor speed using the PID algorithm.
- **Potentiometer Input:** User-friendly interface for setting desired motor speed.
- **Encoder Feedback:** Closed-loop control for enhanced accuracy.
- **LCD Display:** Real-time monitoring of setpoints and actual motor speed.

## Setup and Usage

1. **Upload Code to Arduino:**
- Open the Arduino IDE.
- Load the `PID_controller.ino` file.
- Upload the code to your Arduino board.

2. **Hardware Configuration:**
- Connect the motor, potentiometer, encoder, and LCD based on the provided pin assignments.
- Power on the system.

3. **Tweak PID Constants:**
- Adjust PID constants (`Kp`, `Ki`, `Kd`) in the code for optimal performance based on your motor and system characteristics.

## Contributions

Contributions and suggestions are welcome! If you'd like to contribute or have ideas for improvements, please open an issue or submit a pull request.

