# simhub-e36-cluster
My attempt at making an E36 instrument cluster that works with SimHub. Inspired by [amstudio's E36-Cluster](https://github.com/AM-STUDIO/E36-Cluster-SIMHUB) and built on top of the [SimHub E36 cluster by SHWotever](https://github.com/SHWotever/SimHub/wiki/BMW-E36-Cluster-Setup)

# Differences
Both amstudio's and SHWotever's allow for all the gauges to work such as Speed, RPM, Water Temp, Fuel Percent and Fuel Consumption. However I wanted to make the warning/indicator lamps to work as well. This inspired me to start this project.

# What works and doesnt
## Currently the following works
Gauges
* Speed (from SHWotever)
* RPM (from SHWotever)
* Water Temp (revised work from SHWotever)

Lamps
* Handbrake
* Seatbelt
* Brake Pad (need to restart cluster to turn off again)
* Brake Fluid
* Left Blinker
* Right Blinker
* Dashlight
* High Beams
* Fog Light
* Slip Control

## kinda
* Fuel*

\* inconsistent, for example a partiulcar signal would set the gauge to 50%, then you try it again and it would now set the gauge to 75%. 

## Doesnt
* Fuel Consumption
* ABS lamp (couldn't find how to turn it off ie a pin for it)





