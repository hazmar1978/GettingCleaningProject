Getting and Cleaning Data
Course Project

The R script run_analysis.R does the following:

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive activity names.
5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

Steps to generate tidy_data.txt:
1. Download the following zip file and unzip in working directory (same folder as "run_analysis.R")
   https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 
2. Run "run_analysis.R" 
   source("run_analysis.R")
3. Upon successful execution of step 2 tiny_data.txt will be generated in working directory.

Note: Packages reshape2 and data.table will be installed automatically.