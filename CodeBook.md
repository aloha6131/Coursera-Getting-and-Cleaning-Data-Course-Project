
# Code Book

## Section 1. Merges the training and the test sets to create one data set.
Merge From Below Files:
- features.txt
- activity_labels.txt
- subject_train.txt
- x_train.txt
- y_train.txt
- subject_test.txt
- x_test.txt
- y_test.txt

## Section 2. Extracts only the measurements on the mean and standard deviation for each measurement.
Use "grepl" function to capture "mean" and "std" measurement features

## Section 3. Uses descriptive activity names to name the activities in the data set.
## Section 4. Appropriately label the data set with descriptive activity names.
Give data set a meaningful feature name.

## Section 5.  From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
Write.table
