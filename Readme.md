========================
Name of the Script:

- run_analysis.R
=======================

The goal of the project is to prepare tidy data that can be used for laster analysis.
The following tasks are achieved by running the R script:
1. Merges the training and the test sets to create one dataset
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the dataset.
4. Appropriately labels the dataset with descriptive variable names.
5. Creates a second, independent tidy dataset with the average of each variable for each activity and each subject.
 

R library required:
1. "data.table"
2. "reshape2"

Working directory:
- ./UCI HAR Dataset

Input files required:
1. activity_label2.txt
2. subject_train.txt
3. subject_test.txt
4. X_train.txt
5. X_test.txt
6. y_train.txt
7. y_test.txt
8. features.txt


Running the script:
1. the script can be run line by line in RStudio or
2. run as a whole using source("run_analysis.R")

Outputs
1. a txt file named "clean.txt" will be created in the working directory after the script is successfully completed.








