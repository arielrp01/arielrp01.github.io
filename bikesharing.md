## Data Analysis | Cyclistic Bike Share Case Study
### Introduction

This project was completed for the [Google Data Analytics Capstone](https://www.coursera.org/learn/google-data-analytics-capstone) course and focused on analyzing biksharing data and making recommendations for converting casual users to annual members. 

Deliverables: Analysis report (.Rmd and .md formats), README.md, visualizations, and additional documentation

[View on GitHub](https://github.com/arielrp01/CourseraDataAnalyticsCapstone)

### Dataset

* <b>Dataset</b>: <a href=" https://divvy-tripdata.s3.amazonaws.com/index.html">Cyclistic Data Archive</a> [688.7 MB, 3.4M rows and 13 cols]

* <b>Description</b>: This project used bikesharing data from April 2020 to March 2021. The data has been made available by Motivate International Inc. under this [license](https://ride.divvybikes.com/data-license-agreement). Due to data privacy concerns, the data was anonoymized to protect riders’ personally identifiable information.

### Assignment Requirements

* Select and combine 12 months of data into a single dataset.

* Clean, transform, and analyze the dataset.

* Produce an analysis report with supporting visualizations, key findings, and your top three recommendations.


### Data Manipulation and Transformation

R packages used included tidyverse, DataExplorer, janitor, and lubridate.

* Combined 12 CSVs into a single file.

* Used DataExplorer for advanced data exploration.

* Removed empty columns and rows.

* Created columns for date, month, day, year, weekday, start_hour, end_hour, and season.

* Calculated ride length and create new column.

* Changed data type for ride_length to numeric.

* Omitted NAs, negative trip lengths, and maintenance checks.

More info via the [Cyclistic Bikesharing Case Study .Rmd file](https://github.com/arielrp01/CourseraDataAnalyticsCapstone/blob/main/Cyclistic-Bikesharing-Case-Study.md) and 
the [DataExplorer EDA report](https://drive.google.com/file/d/12HYfKabuqNUeHAMRuPNRDpq28AFsMYEv/view?usp=sharing).


### Additional Information

[Google Data Analytics Capstone: Complete a Case Study](https://www.coursera.org/learn/google-data-analytics-capstone)

[How does a bike-share navigate speedy success?](https://drive.google.com/file/d/1S9OxVsgo6b2K5ovQsHkTQ05ExyqwOfIW/view?usp=sharing) (PDF)
