# Ultrasonic Power Transfer

## Background

[Ultrasonic transducers](https://en.wikipedia.org/wiki/Ultrasonic_transducer) are devices that can convert ultrasonic waves to electrical signals and vice versa. We're going to use this property to design a wireless power system that can power equipment that operates remotely. 

This idea has been implemented in many forms, and the paper, [Ultrasound Sensor-Based Wireless Power Transfer for Low-Power Medical Devices](https://www.researchgate.net/publication/334184504_Ultrasound_Sensor-Based_Wireless_Power_Transfer_for_Low-Power_Medical_Devices), in particular, is what I used as a starting point. The researchers test the efficacy of power transfer between an ultrasonic transmitter driven by a function generator and a receiver whose signal is rectified and amplified to power an Arduino.

## Methodology

### Attempt #1

Methodology: Arduino, ultrasonic sensor to transmit, ultrasonic receiver to receive.

Results: Signal received not big enough to amplify, but a frequency was measured using DMM

### Attempt #2
