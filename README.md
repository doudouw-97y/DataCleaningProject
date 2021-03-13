# DataCleaningProject

## Project Overview
One of the most exciting areas in all of data science right now is wearable computing. Companies like Fitbit, Nike, and Jawbone Up are racing to develop the most advanced algorithms to attract new users. The data used in this project represent data collected from the accelerometers from the Samsung Galaxy S smartphone.

A full description is available at the site where the data was obtained:  
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones 

Here are the data for the project:  
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip  

## Aim of the Project

The goal is to produce a second, independent tidy data set based on the raw data above.

The process of cleaning data and transformation includes the following:
1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names. 
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

## How to use the run_analysis.R script

By running it, the script will perform the following tasks:
1. The script will download and unzip the raw data in the project location. See "UCI HAR Dataset" folder.
2. Then the script will load the data sets from the "test" and "train" subdirectories, and perform merges into one data set.
3. Columns with "mean()" or "std()" in the header name will be extracted.
4. Transform class labels into categorical values with descriptive activity names.
5. Abbreviations in the column names will be transformed into full names.
6. Grouping by subject and activity, the script will calculate the mean for the remaining 68 variables and output to the file names "tidy_data.txt".



