## EDA | Individual Household Electric Power Consumption Dataset
### Introduction

This project was completed for Johns Hopkins University/Coursera [Exploratory Data Analysis](https://www.coursera.org/learn/exploratory-data-analysis) course and focused on EDA and visualization of electric power consumption data. 

Deliverables: R plots and code

[View on GitHub](https://github.com/arielrp01/ExData_Plotting1)

### Dataset

Individual Household Electric Power Consumption Dataset from the <a href="http://archive.ics.uci.edu/ml/">UC Irvine Machine Learning Repository</a>

* <b>Dataset</b>: <a href="https://d396qusza40orc.cloudfront.net/exdata%2Fdata%2Fhousehold_power_consumption.zip">Electric power consumption</a> [20MB, 2.07M rows and 9 cols]

* <b>Description</b>: Measurements of electric power consumption in one household with a one-minute sampling rate over a period of almost 4 years. Different electrical quantities and some sub-metering values are available.

The following descriptions of the 9 variables in the dataset are taken from the <a href="https://archive.ics.uci.edu/ml/datasets/Individual+household+electric+power+consumption">UCI web site</a>:

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


### Assignment Requirements

Completed the following tasks:

* Fork and clone the [Ex_Data_Plotting1 GitHub repository](https://github.com/rdpeng/ExData_Plotting1).

* Reproduce four plots using the base plotting system.

* Push all PNG files and R code files to individual git repository.


### Data Manipulation and Transformation

R packages used included the base plotting system and dplyr.

* Filtered dates of interest, 1/2/2007 and 2/2/2007

* Converted Data and Time with strptime

* Converted Global_active_power to numeric

* Converted Sub_metering values to numeric


### Plots

#### Plot 1
<img src="https://github.com/arielrp01/ExData_Plotting1/blob/master/figure/unnamed-chunk-2.png?raw=true"/>

#### Plot 2
<img src="https://github.com/arielrp01/ExData_Plotting1/blob/master/figure/unnamed-chunk-3.png?raw=true"/>

#### Plot 3
<img src="https://github.com/arielrp01/ExData_Plotting1/blob/master/figure/unnamed-chunk-4.png?raw=true"/>

#### Plot 4
<img src="https://github.com/arielrp01/ExData_Plotting1/blob/master/figure/unnamed-chunk-5.png?raw=true"/>
