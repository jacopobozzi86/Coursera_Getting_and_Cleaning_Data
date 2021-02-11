Getting and Cleaning Data - Course Project
Modifications

- the original data was modifies by
- Merging the training and the test sets to create one data set.
- Extracting only the measurements on the mean and standard deviation for each measurement.
- Useing descriptive activity names to name the activities in the data set
- Appropriately labeling the data set with descriptive variable names.
- Creating a second, independent tidy data set with the average of each variable for each        activity and each subject.

Descriptions
Identifiers
The first two columns - Subject and Activity - are Identifiers.

Subject: the ID of the Subject
Activity: the Name of the Activity performed by the subject when measurements were taken

Measurements
As mentioned above,the variables remaining are just the calculatd means and standard deviations of these sets of data: (Even if I do not give a detailed description of what each data value means, you can see what it means by comparing it with the original data column.)

"TimeBodyAccelerometer.mean...X" 
"TimeBodyAccelerometer.mean...Y" 
"TimeBodyAccelerometer.mean...Z" 
"TimeGravityAccelerometer.mean...X" 
"TimeGravityAccelerometer.mean...Y" 
"TimeGravityAccelerometer.mean...Z" 
"TimeBodyAccelerometerJerk.mean...X"
"TimeBodyAccelerometerJerk.mean...Y"
"TimeBodyAccelerometerJerk.mean...Z"
"TimeBodyGyroscope.mean...X"
"TimeBodyGyroscope.mean...Y" 
"TimeBodyGyroscope.mean...Z" 
"TimeBodyGyroscopeJerk.mean...X" 
"TimeBodyGyroscopeJerk.mean...Y" 
"TimeBodyGyroscopeJerk.mean...Z" 
"TimeBodyAccelerometerMagnitude.mean.." 
"TimeGravityAccelerometerMagnitude.mean.." 
"TimeBodyAccelerometerJerkMagnitude.mean.." 
"TimeBodyGyroscopeMagnitude.mean.." 
"TimeBodyGyroscopeJerkMagnitude.mean.." 
"FrequencyBodyAccelerometer.mean...X" 
"FrequencyBodyAccelerometer.mean...Y" 
"FrequencyBodyAccelerometer.mean...Z" 
"FrequencyBodyAccelerometer.meanFreq...X" 
"FrequencyBodyAccelerometer.meanFreq...Y" 
"FrequencyBodyAccelerometer.meanFreq...Z" 
"FrequencyBodyAccelerometerJerk.mean...X" 
"FrequencyBody