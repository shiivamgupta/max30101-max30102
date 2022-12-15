# max30101-max30102
A MicroPython library for the Maxim MAX30100 pulse oximetry chip
This library provides a basic interface to the MAXIM MAX30100 heart rate and Sp02 sensor chip.

Currently this library supports both IR led (pulse) and red led (SpO2) modes, with support (via gpiozero) for catching on-board interrupts and triggering real-time measurements. The examples below demonstrate a common setup. Calculations for converting measured values into actual number are not yet included.