Getting and Cleaning Data - Course Project

- This is the course project for the Getting and Cleaning Data Coursera course. 
- The included R script, run_analysis.R, conducts the following:

1. Download the dataset from web if it does not already exist in the working directory.
2. Assign all the datafame downloaded to local variables
3. Merge the training(X) set, the test(Y) set, and the subject one to create one data set. 
   The dataset created is called Merged_Data.
4. Extracts only the measurements on the mean and standard deviation for each measurement.
5. Uses descriptive activity(activities) names to name the activities in the data set.
6. Appropriately labels the data set with descriptive variable names.
7. Creates a second independent tidy data set with the average of each variable 
   for each activity and each subject.
