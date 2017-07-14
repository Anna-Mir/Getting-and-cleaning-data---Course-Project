The Data is represented by Coursera:

Companies like Fitbit, Nike, and Jawbone Up are racing to develop the most advanced algorithms to attract new users. The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone. 
A full description is available at the site where the data was obtained:
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Here are the data for the project:
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip


File  "Run_analysis.R" perform 5 following steps according to the request:

1. Downloading and unzipping dataset

2. Merging the training and the test sets to create one data set.
 - Reading files
 - Reading trainings tables
 - Reading testing tables
 - Reading feature vector
 - Reading activity labels
 Assigning column names
 Merging all data in one set
 
3. Extracting only the measurements on the mean and standard deviation for each measurement
- Reading column names
- Create vector for defining ID, mean and standard deviation
- Making nessesary subset from setAllInOne

4. Using the descriptive activity names to name the activities in the data set

5. Creating a second, independent tidy data set with the average of each variable for each activity and each subject
 - Making second tidy data set
 - Writing second tidy data set in txt file
 
 Variables Description:
 
x_train, y_train, x_test, y_test, subject_train and subject_test contain the data from the downloaded files.
x_data, y_data and subject_data merge the previous datasets to further analysis.
features contains the correct names for the x_data dataset, which are applied to the column names stored in

