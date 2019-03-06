# Getting-and-Cleaning-Data-Course-Project
JHU Coursera unit of Data Science Specialization 'Getting and Cleaning Data'

**Synopsis**

This project is from the Coursera course with Johns Hopkins University, Getting and Cleaning Data

The assignment was completed by Stuart Phythian, Student of Business Analytics and also works at Phythian Limited. You can visit us at phythian.co.uk

**Objective**

The issue is that when faced with many lines of data from numerous files, this assignment was to merge, combine and extract specific variables from multiple variables.

Objective 1: download and unzip the data file into your R working directory.

2: download the R source code into your R working directory.

3: execute R source code to generate tidy data file.

**Data description**

The variables in the data are sensor signals measured with waist-mounted smartphone from 30 subjects. The variable in the data indicates activity type the subjects performed during recording.

**Code explanation**

The code combines the training dataset and test dataset into one dataset.
The resulting dataset has the partially extracted Mean and Standard Deviation for each measurement.

**Outcomes**

5 immediate outcomes:

1. Merges the training and the test sets to create one data set. Use command rbind to combine training and test set
2. Extracts only the measurements on the mean and standard deviation for each measurement. Use grep command to get column indexes for variable name contains "mean()" or "std()"
3. Uses descriptive activity names to name the activities in the data set Convert activity labels to characters and add a new column as factor
4. Appropriately labels the data set with descriptive variable names. Give the selected descriptive names to variable columns
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject. Use pipeline command to create a new tidy dataset with command group_by and summarize_each in dplyr package

**Assignment Question**

One of the most exciting areas in all of data science right now is wearable computing - see for example [this article ](http://www.insideactivitytracking.com/data-science-activity-tracking-and-the-battle-for-the-worlds-top-sports-brand/). Companies like Fitbit, Nike, and Jawbone Up are racing to develop the most advanced algorithms to attract new users. The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone. A full description is available at the site where the data was obtained:

<http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones>

Here are the data for the project:

<https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip>
