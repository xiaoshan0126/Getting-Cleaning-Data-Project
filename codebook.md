#Objective
To create a tidy data that could be used later for analysis

#Data Overview
The raw data are obtained from UCI Machine Learning repository. Specifically for this project, we used the Human Activity Recognition Using Smartphones Data Set 
A full description is available at the site where the data was obtained 
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

The data can be found at 
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

#Data Set Information
The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data. 

The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency components, therefore a filter with 0.3 Hz cutoff frequency was used. From each window, a vector of features was obtained by calculating variables from the time and frequency domain.

#Attribute Information
For each record in the dataset it is provided: 
- Triaxial acceleration from the accelerometer (total acceleration) and the estimated body acceleration. 
- Triaxial Angular velocity from the gyroscope. 
- A 561-feature vector with time and frequency domain variables. 
- Its activity label. 
- An identifier of the subject who carried out the experiment.

#Get the Data
Download the file and unzip the file into the work dirctory folder
Using "path_rf <- file.path("./data" , "UCI HAR Dataset")" to get the list of the files. 
For the purposes of this project, the files in the Inertial Signals folders are not used. 
The files that will be used to load data are listed as follows:
- test/subject_test.txt
- test/X_test.txt- 
- test/y_test.txt
- train/subject_train.txt
- train/X_train.txt
- train/y_train.txt

#1. Merge
