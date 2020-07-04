# Getting and Cleaning Data - Course Project

This is the project for the Getting and Cleaning Data course at Coursera.
To run the project you need to do the following:

1. Download the dataset: `https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip`.
2. Load the activity and feature info in ``run_analysis.R``.
3. First loads both the training and test datasets, keeping only the columns which reflect a mean or standard deviation. After that, loads the activity and subject data for each dataset then merges those columns with the dataset.
5. Merges the two differents datasets into the same dataset.
6. Do a conversion of the `activity` and `subject` columns into factors.
7. Finally it creates a tidy dataset that consists of the average value of each variable for each subject and activity pair.

The end result is shown in the file `Tidy_Data.txt`.