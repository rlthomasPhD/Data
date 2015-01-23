# Data

Download the data source ```UCI HAR Dataset``` from
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
Put ```run_analysis.R``` in working directory
Run ```source("run_analysis.R")```, then it will generate a new file ```tiny_data.txt``` in your working directory.
Print tiny_data.txt

run_analysis.R conducts the following:
1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names. 
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
