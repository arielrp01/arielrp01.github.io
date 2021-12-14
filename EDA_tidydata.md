## EDA | UCI HAR Dataset
### Introduction

This project was completed for Johns Hopkins University/Coursera [Getting and Cleaning Data](https://www.coursera.org/learn/data-cleaning) course and focused on EDA and producing a tidy dataset.

Deliverables: Dataset and R code

[View on GitHub](https://github.com/arielrp01/Coursera-Cleaning-Data-Project)

### Dataset

 Data Set from the <a href="http://archive.ics.uci.edu/ml/">UC Irvine Machine Learning Repository</a>

* <b>Dataset</b>: <a href="https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip">UCI HAR Dataset</a> [62.8MB,  10,299 rows and 561 cols]

* <b>Description</b>: Experiments were carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. 

More info at [http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones).


### Assignment Requirements

Completed the following tasks:

* Produce a tidy dataset.

* Create a link to a GitHub repository with the R script.

* Create a code book (CodeBook.md) that describes the variables, the data, and any transformations or work required to clean up the data.

* Include a README.md in the repository.


### Data Manipulation and Transformation

R packages used included dplyr. More info at [CodeBook.md](https://github.com/arielrp01/Coursera-Cleaning-Data-Project/blob/main/CodeBook.md)


### About run_analysis.R

*  Merges the training and the test sets to create one dataset.

*  Extracts only the measurements on the mean and standard deviation for each measurement.

*  Uses descriptive activity names to name the activities in the dataset.

*  Appropriately labels the dataset with descriptive variable names.

*  Creates a second, independent tidy dataset (TidyData.txt) with the average of each variable for each activity and each subject.

