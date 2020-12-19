# Experiment 1: Transmitting with Ultrasonic Sensors

## Introduction

In this preliminary experiment, we'll attempt wirelessly powering an LED with the voltage produced across a receiver's terminals from the ultrasonic waves
transmitted by an ultrasonic sensor connected to an Arduino.

## Methods

Our setup consists of an Arduino, [HC-SR04 Ultrasonic Distance Sensor](https://www.sparkfun.com/products/15569), 
and [TCT40-16R Ultrasonic transducer](https://www.lxxtech.com/tct40-16rt-rt-split-ultrasound-ultrasonic-sensor-ultrasonic-probe-center-frequency-40khz-dia-p433.html).
The advantage of using the off-the-shelf sensor to drive the transmitter is that we can interface with it easily. Writing a digital high to the TRIG pin of 
the sensor tells the transmitter to emit 8 consecutive 40kHz (ultrasonic) pulses. These pulses are caught by the receiver placed in the transmitter's line of sight, 
which are then transformed to electrical pulses across its terminals.

The ultrasonic sensor's VCC, TRIG, ECHO, and GND pins are wired to the Arduino's DC 5V, two digital pins, and ground respectively. The following schematic is from an article on [Last Minute Engineers](https://lastminuteengineers.com/arduino-sr04-ultrasonic-sensor-tutorial/).

## Results



## Discussion
