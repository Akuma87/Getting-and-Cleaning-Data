# Getting-and-Cleaning-Data
Introduction

This repository contains my work for the course project for the Coursera course "Getting and Cleaning data".
About the raw data

The features (561 of them) are unlabeled and can be found in the x_test.txt. The activity labels are in the y_test.txt file. The test subjects are in the subject_test.txt file.

The same holds for the training set.

I created a script called run_analysis.R which will merge the test and training sets together.

Lastly, the script will create a tidy data set containing the means of all the columns per test subject and per activity. This tidy dataset will be written to a tab-delimited file called tidy.txt, which can also be found in this repository.

About the Code Book

The CodeBook.md file explains the transformations performed and the resulting data and variables.
