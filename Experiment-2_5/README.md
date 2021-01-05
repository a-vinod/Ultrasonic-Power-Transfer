# Experiment 2_5: Optimizing Tx-Rx Separation Distances for Power Transfer

## Introduction

This experiment is an addendum to Experiment 2 where we found that the Rx voltage for when the Tx-Rx distance is 10mm is greater than when it's 5mm. Strangely, more power was transfered at a greater distance. We investigate this behavior in this experiment. 

![](docs/tx-rx.gif) | ![](docs/waveform.gif)
---|---

## Methods

This experiment's setup is identical to that of Experiment 2. We found the distances where the votlage across the receiver is at a local maxima and minima for a couple of trials. Starting at the closest distance between the receiver and transmitter where the Rx voltage is at a local maxima, we increase the distance between them until the Rx voltage local minima. Then, we pull it apart further until the Tx voltage is a local maxima again. The distances and Rx voltages are recorded at each one of these instances.

## Results

When pulling the transmitter and receiver apart, we find that the voltage across the receiver, and thus the power transferred, oscillates between local maximas and minimas. See the animation in the Introduction.

Below is the Tx-Rx distance and Rx voltage for each data point of a maxima or minima, along with a scatter plot visualizing the data.

![](docs/data_table.png)

![](docs/data_plot.png)

## Discussion

Initially, we assumed that minimizing the distance between the transducers would maximize the power transferred. However, we found that there are local maxima and minima values of Rx voltage in a range of Tx-Rx separation distances. Hence, to optimize the power transferred, we might place the receiver and transmitter further apart than required. This is counterinuitive at first, but there are some possible causes of this behavior.

One reason is if some of the ultrasonic waves bounced off the rim of the receiver, bounced off the rim of the transmitter, and then constructively interfered with the original waves to produce a larger voltage. This would explain the existence of both the maxima and minima since these waves would alternate between acting constructively and destructively.
