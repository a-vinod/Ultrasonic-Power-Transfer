[Ultrasonic transducers](https://en.wikipedia.org/wiki/Ultrasonic_transducer) are devices that can convert ultrasonic waves to electrical signals and vice versa. We're going to use this property to design a wireless power system that can power equipment that operates remotely. 

This idea has been implemented in many forms, and the paper, [Ultrasound Sensor-Based Wireless Power Transfer for Low-Power Medical Devices](https://www.researchgate.net/publication/334184504_Ultrasound_Sensor-Based_Wireless_Power_Transfer_for_Low-Power_Medical_Devices), is what I used as a starting point. The researchers test the efficacy of power transfer between an ultrasonic transmitter driven by a function generator and a receiver that has its signal rectified and amplified to power an Arduino.

This repository consists of the series of experiments I'm conducting, each building on the last.

# Experiments

[[1](Experiment-1)] Transmitter Driven by Ultrasonic Sensor

[[2](Experiment-2)] Transmitter Driven by Picoscope Arbitrary Waveform Generator

[[2.5](Experiment-2_5)] Transmitter Driven by Picoscope Arbitrary Waveform Generator - Exploring the transducers' oscillatory behavior to find optimal Tx-Rx separation distances for power transfer 

[3] Transmitter Driven by amplified Picoscope Arbitrary Waveform Generator
