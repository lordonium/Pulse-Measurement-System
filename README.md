<p align="center"><img width=100% src="https://github.com/lordonium/Pulse-Measurement-System/blob/master/media/logo.png"></p>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![LabVIEW](https://img.shields.io/badge/LabVIEW-v2015.1-yellow.svg)
![Dependencies](https://img.shields.io/badge/dependencies-up%20to%20date-brightgreen.svg)
![Contributions welcome](https://img.shields.io/badge/contributions-welcome-orange.svg)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)

## Basic Overview
While conducting an experiment you can use different techniques for measuring the signals. I was asked to code  **Keithley 2182A Nanovoltemeter** in conjunction with **6221 DC and AC Current Source** to perfom Pulse Delta and Delta measurements. 

## Theory
Before explaining the software part lets tackle a little bit of theory.

### Delta
Delta voltage measurements use a current-reversal technique to cancel the
effects of thermal EMFs in the voltmeter test lead connections. The simplest
algorithm for a delta measurement uses the following 2-point source/measure
process:

1. Source a positive current through the DUT and measure the voltage (V1).
2. Source a negative current through the DUT and measure the voltage (V2).
3. Calculate the delta reading as follows:

![equation](http://latex.codecogs.com/gif.latex?delta&space;=&space;(V1-V2)/2)

## Authors

* **Sergey Chernayev** - *Initial work* - [lordonium](https://github.com/lordonium)

All other known bugs and fixes can be sent to chernayev.sergey.work@gmail.com

Reported bugs/fixes will be submitted to correction
<!-- See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.
 -->
## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details