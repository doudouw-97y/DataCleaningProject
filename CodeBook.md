# The codebook for the tidy data set

## Overview
The tidy data set, "tidy_data.txt", is a table with the first two columns as subject and activitiy, and the rest of columns variables relating to accelerometer and gyroscope data.

## Variables
1. Subejct: 30 participants who were using the smartphone in the experiment.  
2. Activities: 6 different physical activities which were used to measure the accelerometer and gyroscope data. They are walking, walking upstairs, walking downstairs, standing, sitting, laying.   
3. Features: The details of these measurements can be looked up in the Appendix below.

## Transformation
1. The data are merged for processing.
2. The wanted features are defined as mean and standard deviations of each measurement. Remaining features are excluded from the data set.
3. Quantitative variable, Activity label ranging from 1 to 6, are transformed into categorical variable i.e. activity names such as "WALKING" etc.
4. The data set is then grouped by subject and activity, finally means for all the measurements are populated.
5. The tidy data set is saved in file with text format, setting row.name=FALSE.