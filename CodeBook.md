There are 5 parts:

## Merges the training and the test sets to create one data set.
##Extracts only the measurements on the mean and SD for each measurement.
##Uses descriptive activity names to name the activiities in the data set.
##Appropriately labels the data set with descriptive activity names.
##Creates a second, independent tidy data set with the average of each variable for each activity and each subject.


How "run_analysis.R" implements the above steps:

##Require reshapre2 and data.table libraries.
##Load both test and train data
##Load the features and activity labels.
##Extract the mean and standard deviation column names and data.
##Process the data. There are two parts processing test and train data respectively.
##Merge data set.
