# Experiment 2: Function Generator Driven Transmitter

## Introduction

From Experiment 1, we concluded that the ultrasonic waves emitted by the ultrasonic sensor lost too much energy while being transmitted in the air to produce a large enough voltage across the receiver terminals to power an LED. For more granular control and the ability to increase the amplitude of the 40kHz electric pulses into the transmitter, we're going to use a Picoscope's arbitrary waveform generator. The Picoscope will also allow us to measure the signal on the receiver terminals accurately as well.


## Methods

Below is the schematic of the circuit we implement for this experiment.

![Tx-Rx Schematic](docs/AWG_TxRx_Schematic.png)


And below are photos of the implemented circuit. The transmitter and receiver circuits are on the right and left side respectively.

Top View                   |  Side View
:-------------------------:|:-------------------------:
![](docs/AWG_TopView.jpg)  |  ![](docs/AWG_SideView.jpg)

The transmitter circuit is driven by voltage from the AWG and the scope's probe is measuring the voltage across the terminals of the receiver. We'll drive the AWG with a range of voltages from 0V to 2V and measure the AC voltage induced at the receiver terminals

## Results

For each amplitude driven by the AWG, we recorded the measurement of maxmium and minimum amplitude of the Rx voltage from a window of the Picoscope software once the waveform stabilized. For example, the waveform observed at the Rx with the AWG driving 2V is shown below.

![](measurements/Picoscope_example/Picoscope_example_01.jpg )

Below is a table summarizing our measurements. The raw data can be observed in the `measurements` folder both as psdata and CSVs.

AWG Driving Voltage (mV)   |  Maximum Rx Voltage (mV)  |  Minimum Rx Voltage (mV) |
:-------------------------:|:-------------------------:|:-------------------------:
500 	                     |  151.8052 	               |  -153.4226
600 	                     |  180.0348 	               |  -181.6523
700 	                     |  212.6987 	               |  -215.1860
800 	                     |  239.1583 	               |  -241.6608
900 	                     |  270.0430 	               |  -276.9555
1000 	                     |  300.9277 	               |  -303.4150
2000 	                     |  594.5005 	               |  -595.6298

And below is a scatter plot of the summarized measurements.

![](measurements/index.png)

## Discussion

TODO
