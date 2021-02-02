# Household-Electric-Power-Consumption

This project uses "Individual household
electric power consumption Data Set" from
the <a href="http://archive.ics.uci.edu/ml/">UC Irvine Machine
Learning Repository</a>. 

### About the project
* <b>Dataset</b>: <a href="https://d396qusza40orc.cloudfront.net/exdata%2Fdata%2Fhousehold_power_consumption.zip">Electric power consumption</a> [20Mb]

* <b>Description</b>: Measurements of electric power consumption in
one household with a one-minute sampling rate over a period of almost
4 years. Different electrical quantities and some sub-metering values
are available.


The following descriptions of the 9 variables in the dataset are taken
from
the <a href="https://archive.ics.uci.edu/ml/datasets/Individual+household+electric+power+consumption">UCI
web site</a>:

<ol>
<li><b>Date</b>: Date in format dd/mm/yyyy </li>
<li><b>Time</b>: time in format hh:mm:ss </li>
<li><b>Global_active_power</b>: household global minute-averaged active power (in kilowatt) </li>
<li><b>Global_reactive_power</b>: household global minute-averaged reactive power (in kilowatt) </li>
<li><b>Voltage</b>: minute-averaged voltage (in volt) </li>
<li><b>Global_intensity</b>: household global minute-averaged current intensity (in ampere) </li>
<li><b>Sub_metering_1</b>: energy sub-metering No. 1 (in watt-hour of active energy). It corresponds to the kitchen, containing mainly a dishwasher, an oven and a microwave (hot plates are not electric but gas powered). </li>
<li><b>Sub_metering_2</b>: energy sub-metering No. 2 (in watt-hour of active energy). It corresponds to the laundry room, containing a washing-machine, a tumble-drier, a refrigerator and a light. </li>
<li><b>Sub_metering_3</b>: energy sub-metering No. 3 (in watt-hour of active energy). It corresponds to an electric water-heater and an air-conditioner.</li>
</ol>


### Result
This project aims to examine how household energy usage
varies over a 2-day period in February, 2007. Data from the dates 2007-02-01 and 2007-02-02 will only be used for exploratory analysis.

#### Histogram of global active power
![plot of chunk unnamed-chunk-2](figure/unnamed-chunk-2.png) 

#### Time-series plot on global active power
![plot of chunk unnamed-chunk-3](figure/unnamed-chunk-3.png) 

#### Time-series plot on energy sub-metering
![plot of chunk unnamed-chunk-4](figure/unnamed-chunk-4.png) 


#### Time-series plots on global active power, voltage, energy sub-metering and global reactive power
![plot of chunk unnamed-chunk-5](figure/unnamed-chunk-5.png) 

