# Project: Getting and Cleaning Data
The purpose of the project is to demonstrate ability to collect, work with, and clean a data set.

## Project Description

The goal is to prepare tidy data that can be used for later analysis. You will be graded by your peers on a series of yes/no questions related to the project. You will be required to submit: 

1. A tidy data set (tiny_data.txt) as a result the R script run_analysis.R.
2. A link to a Github repository with your script for performing the analysis.
3. A code book that describes the variables, the data, and any transformations or work that you performed to clean up the data called CodeBook.md.
4. Also include a README.md in the repo that explains how all of the scripts work and how they are connected.  


R script called run_analysis.R should do the following:

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive activity names.
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

## Project Execution

1. Download and copy the data source directory ```UCI HAR Dataset``` into any folder.
2. Copy ```run_analysis.R``` into the same folder into which data source direcotry is copied.
3. Set the folder as your working directory in R.
3. Run the R script ```source("run_analysis.R")```.
4. It will generate a new file ```tiny_data.txt``` in the working directory.
