run_analysis.R calculates the average of columns based on the "Human Activity Recognition Using Smartphones Dataset".
The data is grouped by activities and subjects, over which the average has been calculated for each column that describes a feature.

In the produced dataset, there is one column "activity" specifying the activity (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) and one column "subject" that specifies subject id (1-30). 
This is followed by a number of columns that specify features, calculated as the mean over the corresponding measurements.
These features are normalized and bounded within [-1,1].

The features are:

 [1] "tBodyAcc-mean()-X"           "tBodyAcc-mean()-Y"           "tBodyAcc-mean()-Z"           "tGravityAcc-mean()-X"       
 [5] "tGravityAcc-mean()-Y"        "tGravityAcc-mean()-Z"        "tBodyAccJerk-mean()-X"       "tBodyAccJerk-mean()-Y"      
 [9] "tBodyAccJerk-mean()-Z"       "tBodyGyro-mean()-X"          "tBodyGyro-mean()-Y"          "tBodyGyro-mean()-Z"         
[13] "tBodyGyroJerk-mean()-X"      "tBodyGyroJerk-mean()-Y"      "tBodyGyroJerk-mean()-Z"      "tBodyAccMag-mean()"         
[17] "tGravityAccMag-mean()"       "tBodyAccJerkMag-mean()"      "tBodyGyroMag-mean()"         "tBodyGyroJerkMag-mean()"    
[21] "fBodyAcc-mean()-X"           "fBodyAcc-mean()-Y"           "fBodyAcc-mean()-Z"           "fBodyAccJerk-mean()-X"      
[25] "fBodyAccJerk-mean()-Y"       "fBodyAccJerk-mean()-Z"       "fBodyGyro-mean()-X"          "fBodyGyro-mean()-Y"         
[29] "fBodyGyro-mean()-Z"          "fBodyAccMag-mean()"          "fBodyBodyAccJerkMag-mean()"  "fBodyBodyGyroMag-mean()"    
[33] "fBodyBodyGyroJerkMag-mean()" "tBodyAcc-std()-X"            "tBodyAcc-std()-Y"            "tBodyAcc-std()-Z"           
[37] "tGravityAcc-std()-X"         "tGravityAcc-std()-Y"         "tGravityAcc-std()-Z"         "tBodyAccJerk-std()-X"       
[41] "tBodyAccJerk-std()-Y"        "tBodyAccJerk-std()-Z"        "tBodyGyro-std()-X"           "tBodyGyro-std()-Y"          
[45] "tBodyGyro-std()-Z"           "tBodyGyroJerk-std()-X"       "tBodyGyroJerk-std()-Y"       "tBodyGyroJerk-std()-Z"      
[49] "tBodyAccMag-std()"           "tGravityAccMag-std()"        "tBodyAccJerkMag-std()"       "tBodyGyroMag-std()"         
[53] "tBodyGyroJerkMag-std()"      "fBodyAcc-std()-X"            "fBodyAcc-std()-Y"            "fBodyAcc-std()-Z"           
[57] "fBodyAccJerk-std()-X"        "fBodyAccJerk-std()-Y"        "fBodyAccJerk-std()-Z"        "fBodyGyro-std()-X"          
[61] "fBodyGyro-std()-Y"           "fBodyGyro-std()-Z"           "fBodyAccMag-std()"  