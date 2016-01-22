Description: R script called run_analysis.R that does the following

1. Merges the training and the test sets to create one data set
2. Extract only measurements of mean and standard deviation for each measurement
3. Use descriptive activity names to name the activities in the data set (for consistency, original column names have been retained)
4. From the data set in step 4, script returns an independent tidy data set with average of each variable for each activity and each subject

Dataset:
1. 'README.md'
2. 'run_analysis.R'	R Script
3. 'features.txt' 	List of all features.

Notes: 
Calculate "average" for each data frame column that listed "mean" and SD":
1. Triaxial acceleration from the accelerometer (total acceleration) and the estimated body acceleration.
2. Triaxial Angular velocity from the gyroscope. 
3. 88-feature vector with time and frequency domain variables (filtered to include "mean" and "SD" only)

References: 
Human Activity Recognition Using Smartphones Dataset Version 1.0

Authors:
Jorge L. Reyes-Ortiz, Davide Anguita, Alessandro Ghio, Luca Oneto.
Smartlab - Non Linear Complex Systems Laboratory
DITEN - Università degli Studi di Genova.
Via Opera Pia 11A, I-16145, Genoa, Italy.
activityrecognition@smartlab.ws
www.smartlab.ws# GettingCleaningData-Project 
# GettingCleaningData-Project 
