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

## Apendix
Features list:
 [1] "Subject_ID"                                                           
 [2] "Activity_name"                                                        
 [3] "TimeDomainBodyAcceleration-Mean-X"                                    
 [4] "TimeDomainBodyAcceleration-Mean-Y"                                    
 [5] "TimeDomainBodyAcceleration-Mean-Z"                                    
 [6] "TimeDomainBodyAcceleration-StandardDeviation-X"                       
 [7] "TimeDomainBodyAcceleration-StandardDeviation-Y"                       
 [8] "TimeDomainBodyAcceleration-StandardDeviation-Z"                       
 [9] "TimeDomainGravityAcceleration-Mean-X"                                 
[10] "TimeDomainGravityAcceleration-Mean-Y"                                 
[11] "TimeDomainGravityAcceleration-Mean-Z"                                 
[12] "TimeDomainGravityAcceleration-StandardDeviation-X"                    
[13] "TimeDomainGravityAcceleration-StandardDeviation-Y"                    
[14] "TimeDomainGravityAcceleration-StandardDeviation-Z"                    
[15] "TimeDomainBodyAccelerationJerk-Mean-X"                                
[16] "TimeDomainBodyAccelerationJerk-Mean-Y"                                
[17] "TimeDomainBodyAccelerationJerk-Mean-Z"                                
[18] "TimeDomainBodyAccelerationJerk-StandardDeviation-X"                   
[19] "TimeDomainBodyAccelerationJerk-StandardDeviation-Y"                   
[20] "TimeDomainBodyAccelerationJerk-StandardDeviation-Z"                   
[21] "TimeDomainBodyAngularVelocity-Mean-X"                                 
[22] "TimeDomainBodyAngularVelocity-Mean-Y"                                 
[23] "TimeDomainBodyAngularVelocity-Mean-Z"                                 
[24] "TimeDomainBodyAngularVelocity-StandardDeviation-X"                    
[25] "TimeDomainBodyAngularVelocity-StandardDeviation-Y"                    
[26] "TimeDomainBodyAngularVelocity-StandardDeviation-Z"                    
[27] "TimeDomainBodyAngularVelocityJerk-Mean-X"                             
[28] "TimeDomainBodyAngularVelocityJerk-Mean-Y"                             
[29] "TimeDomainBodyAngularVelocityJerk-Mean-Z"                             
[30] "TimeDomainBodyAngularVelocityJerk-StandardDeviation-X"                
[31] "TimeDomainBodyAngularVelocityJerk-StandardDeviation-Y"                
[32] "TimeDomainBodyAngularVelocityJerk-StandardDeviation-Z"                
[33] "TimeDomainBodyAccelerationMagnitude-Mean"                             
[34] "TimeDomainBodyAccelerationMagnitude-StandardDeviation"                
[35] "TimeDomainGravityAccelerationMagnitude-Mean"                          
[36] "TimeDomainGravityAccelerationMagnitude-StandardDeviation"             
[37] "TimeDomainBodyAccelerationJerkMagnitude-Mean"                         
[38] "TimeDomainBodyAccelerationJerkMagnitude-StandardDeviation"            
[39] "TimeDomainBodyAngularVelocityMagnitude-Mean"                          
[40] "TimeDomainBodyAngularVelocityMagnitude-StandardDeviation"             
[41] "TimeDomainBodyAngularVelocityJerkMagnitude-Mean"                      
[42] "TimeDomainBodyAngularVelocityJerkMagnitude-StandardDeviation"         
[43] "FrequencyDomainBodyAcceleration-Mean-X"                               
[44] "FrequencyDomainBodyAcceleration-Mean-Y"                               
[45] "FrequencyDomainBodyAcceleration-Mean-Z"                               
[46] "FrequencyDomainBodyAcceleration-StandardDeviation-X"                  
[47] "FrequencyDomainBodyAcceleration-StandardDeviation-Y"                  
[48] "FrequencyDomainBodyAcceleration-StandardDeviation-Z"                  
[49] "FrequencyDomainBodyAccelerationJerk-Mean-X"                           
[50] "FrequencyDomainBodyAccelerationJerk-Mean-Y"                           
[51] "FrequencyDomainBodyAccelerationJerk-Mean-Z"                           
[52] "FrequencyDomainBodyAccelerationJerk-StandardDeviation-X"              
[53] "FrequencyDomainBodyAccelerationJerk-StandardDeviation-Y"              
[54] "FrequencyDomainBodyAccelerationJerk-StandardDeviation-Z"              
[55] "FrequencyDomainBodyAngularVelocity-Mean-X"                            
[56] "FrequencyDomainBodyAngularVelocity-Mean-Y"                            
[57] "FrequencyDomainBodyAngularVelocity-Mean-Z"                            
[58] "FrequencyDomainBodyAngularVelocity-StandardDeviation-X"               
[59] "FrequencyDomainBodyAngularVelocity-StandardDeviation-Y"               
[60] "FrequencyDomainBodyAngularVelocity-StandardDeviation-Z"               
[61] "FrequencyDomainBodyAccelerationMagnitude-Mean"                        
[62] "FrequencyDomainBodyAccelerationMagnitude-StandardDeviation"           
[63] "FrequencyDomainBodyBodyAccelerationJerkMagnitude-Mean"                
[64] "FrequencyDomainBodyBodyAccelerationJerkMagnitude-StandardDeviation"   
[65] "FrequencyDomainBodyBodyAngularVelocityMagnitude-Mean"                 
[66] "FrequencyDomainBodyBodyAngularVelocityMagnitude-StandardDeviation"    
[67] "FrequencyDomainBodyBodyAngularVelocityJerkMagnitude-Mean"             
[68] "FrequencyDomainBodyBodyAngularVelocityJerkMagnitude-StandardDeviation"