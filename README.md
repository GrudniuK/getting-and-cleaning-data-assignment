Getting and Cleaning Data Course Project
========================================

# run_analysis.R

This R script does the following, as per the project assignment instructions:

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive activity names. 
5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject. 

## how to run it

In the R enviroment, load the script:

```
source('run_analysis.R')
```

This will download the corpus, unzip it and process it. The end result is a file called **'final_tidy_dataset.txt'** in the **output**

## final tidy dataset

Each row in the final, clean dataset contains subject, activity, and measures for all required features (i.e., mean or standard deviation)
