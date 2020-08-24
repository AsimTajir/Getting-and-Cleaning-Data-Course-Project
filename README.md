# Getting-and-Cleaning-Data-Course-Project
1. activity_labels.txt is loaded in the variable activityLabel.
2. feature.txt is loaded in the variable features.
3. features is filtered and the only the data with mean and std is stored in measurement.
4. X_train.txt, Y_train.txt, subject_train.txt are loaded to variable train, trainActivities,              trainSubjects respectively and then cbind to train.
5. X_test.txt, Y_test.txt, subject_test.txt are stored in test, testActivities, testSubjects                respectively and then cbind to test.
6. train and test are rbinded and stored to combined.
7. Further the combined is reshaped as required and stored to combined.
8. combined is written to a table with file name "tidyData.txt".
