## Data Analysis | Activity Monitoring Device Report
### Introduction

This project was completed for Johns Hopkins University/Coursera [Reproducible Research](https://www.coursera.org/learn/reproducible-research) course and focused on analyzing data from a personal activity monitoring device.

Deliverables: Data analysis report (.Rmd, .md, and HTML formats], README.md, and visualizations 

[View on GitHub](https://github.com/arielrp01/RepData_PeerAssessment1)

### Dataset

* <b>Dataset</b>: <a href="https://d396qusza40orc.cloudfront.net/repdata%2Fdata%2Factivity.zip">Activity Monitoring Dataset</a> [52K, 17,568 rows and 3 cols]

* <b>Description</b>: The device collects data at 5-minute intervals through out the day. The data consists of two months of data from an anonymous individual collected during the months of October and November 2012 and include the number of steps taken in 5-minute intervals each day.

The variables included in this dataset are:

* **steps**: Number of steps taking in a 5-minute interval (missing values are coded as `NA`)

* **date**: The date on which the measurement was taken in YYYY-MM-DD format

* **interval**: Identifier for the 5-minute interval in which measurement was taken


### Assignment Requirements

* Write a data analysis report. More info at [README.md](https://github.com/arielrp01/RepData_PeerAssessment1).

* Produce a single R markdown document that can be processed by knitr and be transformed into an HTML file.

* Fork/clone the [GitHub repository](http://github.com/rdpeng/RepData_PeerAssessment1) created for this assignment.

* Push completed files into the forked repository on GitHub.

* Submit assignment with a URL to the GitHub repository and the the SHA-1 commit ID for the repository state.

### Data Manipulation and Transformation

R packages used included ggplot2, lubridate, and dplyr.

* Reformated date column

* Imputed missing values using interval mean to fill in for NA values

* Created a new factor variable in the dataset with two levels – “weekday” and “weekend” indicating whether a given date is a weekday or weekend day
