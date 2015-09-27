The codebook explains various variables and names

The raw data is in multiple data sets for the experiement. 
It contains the activity labele in activity_lables.txt and features in features.txt
While the activity lables are straight forwards as below; there are multiple features.
Activity Labels
1 WALKING
2 WALKING_UPSTAIRS
3 WALKING_DOWNSTAIRS
4 SITTING
5 STANDING
6 LAYING
We need to extract only the variables that are measuring the mean and standard deviation of each measurement

The train data is in three files x_train and y_train and subjec_train. We need to create a new table with all these 3 tables using cbind and retain only the columns with features as extraced before

Similar excercise is to be done for the test data sets which is again in 3 text files - x_test, y_test and subject_test

Then merge both the test and train datasets using rbind.





