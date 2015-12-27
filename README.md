# Getting and Cleaning Data Project

The purpose of this project is to demonstrate our ability to collect, work with, and clean a data set. The goal is to prepare a tidy data that can be used for later analysis. The original dataset is of accelerometers data from the Samsung Galaxy S smartphone (http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones).


The project instructions are as follows:

You should create one R script called run_analysis.R that does the following. 
Merges the training and the test sets to create one data set.
Extracts only the measurements on the mean and standard deviation for each measurement. 
Uses descriptive activity names to name the activities in the data set
Appropriately labels the data set with descriptive variable names. 
From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.


This Github repository provides a script (run_analysis.R), a tidy dataset (tidydata.txt), and a codebook (CodeBook.md).


## run_analysis.R

The script was implemented in RStudio and performs the following tasks:

Loads the relevant libraries.
Loads the training and test data and merges them.
Adds descriptive variable names.
Keeps only the mean and standard deviation data.
Creates a tidy data set with the average of each variable for each activity and each subject.
The steps are documented in greater detail in CodeBook.md.


## CodeBook.md

The CodeBook contains a description of the variables, the data, and all transformations performed to clean up the data.