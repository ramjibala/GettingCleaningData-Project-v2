Description: R script called run_analysis.R that does the following
1. Merges the training and the test sets to create one data set
2. Extract only measurements of mean and standard deviation for each measurement
3. Use descriptive activity names to name the activities in the data set (for consistency, original column names have been retained)
4. From the data set in step 4, script returns an independent tidy data set with average of each variable for each activity and each subject

Files:
1. 'README.md'		References & Author Acknowledgments
2. 'run_analysis.R'	R Script
3. 'features.txt' 	List of all features (tidy_dataset Column Names)

Activity (ID & Description):
1 WALKING
2 WALKING_UPSTAIRS
3 WALKING_DOWNSTAIRS
4 SITTING
5 STANDING
6 LAYING

Activity ID is Column #2 in file "tidy_dataset"