Codebook

Description
The original data set was obtained from 
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

The experiments involved 30 subjects. Each subject performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) with a sensor-equipped smartphone attached to their waist. The smartphone's accelerometer and gyroscope we used to capture 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz.

Variables
x_train, y_train, x_test, y_test, subject_train and subject_test contain the data from the downloaded files.
x_data, y_data and subject_data merge the previous datasets to further analysis.
all_data merges x_data, y_data and subject_data in a big dataset.
Averages_data contains the relevant averages which will be later stored in a .txt file. ddply() from the plyr package is used to apply colMeans() and ease the development.
