# Getting-and-Cleaning-Data-Project
This project is a final assignment to demostrate learned abilities of the Getting and Cleaning Data Course from Coursera. The files involved are:

1. [Data set](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip) The data linked represents data collected from the accelerometers from the Samsung Galaxy S smartphone. A full description is available at the [site](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones).
2. CodeBook.md: A code book describing each variable and its values in the tidy data set.
3. run_analysis.R:  this file contains the R script that proccess the data with the indicated instructions:
	* Merges the training and the test sets to create one data set.
	* Extracts only the measurements on the mean and standard deviation for each measurement.
	* Uses descriptive activity names to name the activities in the data set
	* Appropriately labels the data set with descriptive variable names.
	* From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
4. OutputData.txt: is the final processed data with the steps in run_analysis.R
