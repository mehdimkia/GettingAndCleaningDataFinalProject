# Code Book for the Tidy Dataset

## Description
This code book describes the variables in the tidy dataset produced by `run_analysis.R`.

## Data Source
The data is sourced from the Human Activity Recognition Using Smartphones Dataset, which includes measurements from the accelerometer and gyroscope of a Samsung Galaxy S II smartphone.

## Variables
- `subject`: The ID of the participant (1-30).
- `activity`: The type of activity performed (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING).
- `TimeBodyAccelerometerMeanX`, `TimeBodyAccelerometerMeanY`, `TimeBodyAccelerometerMeanZ`: Mean values of the body acceleration signals in X, Y, and Z directions.
- `TimeBodyAccelerometerSTD_X`, `TimeBodyAccelerometerSTD_Y`, `TimeBodyAccelerometerSTD_Z`: Standard deviation of the body acceleration signals in X, Y, and Z directions.
- (Include descriptions for all other variables in the tidy dataset.)

## Transformations
- Merged the training and test sets to create one dataset.
- Extracted only the measurements on the mean and standard deviation for each measurement.
- Used descriptive activity names to name the activities in the dataset.
- Labeled the dataset with descriptive variable names.
- Created a second, independent tidy dataset with the average of each variable for each activity and each subject.
