# Downloads data if the current folder does not have it (rows 2 to 4)

# Unzips downloaded file into folder (row 7)

# Obtain list of files and prints(rows 10 to 12)

# Reading activity files (rows 15 and 16)

# Reading subject files (rows 19 and 20)

# REading features files (rows 23 and 24)

# Concatenate the tables by rows using rbind (rows 27 to 29)

# Give the variables names (rows 32 to 35)

# After combining the tables by rows, all of the data are combined by columns (rows 38 and 39)

# Extracting values of names of features with mean and standard deviation (row 42)

# Subsetting the data frame by names of the features (rows 45 and 46)

# Reading table of activity into activityLabels (rows 49 and 50)

# Subbing short names to something more readable (rows 53 to 58)

[1] "timeimeBodyAccelerometerelerometer-mean()-X"                           
 [2] "timeimeBodyAccelerometerelerometer-mean()-Y"                           
 [3] "timeimeBodyAccelerometerelerometer-mean()-Z"                           
 [4] "timeimeBodyAccelerometerelerometer-std()-X"                            
 [5] "timeimeBodyAccelerometerelerometer-std()-Y"                            
 [6] "timeimeBodyAccelerometerelerometer-std()-Z"                            
 [7] "timeimeGravityAccelerometerelerometer-mean()-X"                        
 [8] "timeimeGravityAccelerometerelerometer-mean()-Y"                        
 [9] "timeimeGravityAccelerometerelerometer-mean()-Z"                        
[10] "timeimeGravityAccelerometerelerometer-std()-X"                         
[11] "timeimeGravityAccelerometerelerometer-std()-Y"                         
[12] "timeimeGravityAccelerometerelerometer-std()-Z"                         
[13] "timeimeBodyAccelerometerelerometerJerk-mean()-X"                       
[14] "timeimeBodyAccelerometerelerometerJerk-mean()-Y"                       
[15] "timeimeBodyAccelerometerelerometerJerk-mean()-Z"                       
[16] "timeimeBodyAccelerometerelerometerJerk-std()-X"                        
[17] "timeimeBodyAccelerometerelerometerJerk-std()-Y"                        
[18] "timeimeBodyAccelerometerelerometerJerk-std()-Z"                        
[19] "timeimeBodyGyroscopescope-mean()-X"                                    
[20] "timeimeBodyGyroscopescope-mean()-Y"                                    
[21] "timeimeBodyGyroscopescope-mean()-Z"                                    
[22] "timeimeBodyGyroscopescope-std()-X"                                     
[23] "timeimeBodyGyroscopescope-std()-Y"                                     
[24] "timeimeBodyGyroscopescope-std()-Z"                                     
[25] "timeimeBodyGyroscopescopeJerk-mean()-X"                                
[26] "timeimeBodyGyroscopescopeJerk-mean()-Y"                                
[27] "timeimeBodyGyroscopescopeJerk-mean()-Z"                                
[28] "timeimeBodyGyroscopescopeJerk-std()-X"                                 
[29] "timeimeBodyGyroscopescopeJerk-std()-Y"                                 
[30] "timeimeBodyGyroscopescopeJerk-std()-Z"                                 
[31] "timeimeBodyAccelerometerelerometerMagnitudenitude-mean()"              
[32] "timeimeBodyAccelerometerelerometerMagnitudenitude-std()"               
[33] "timeimeGravityAccelerometerelerometerMagnitudenitude-mean()"           
[34] "timeimeGravityAccelerometerelerometerMagnitudenitude-std()"            
[35] "timeimeBodyAccelerometerelerometerJerkMagnitudenitude-mean()"          
[36] "timeimeBodyAccelerometerelerometerJerkMagnitudenitude-std()"           
[37] "timeimeBodyGyroscopescopeMagnitudenitude-mean()"                       
[38] "timeimeBodyGyroscopescopeMagnitudenitude-std()"                        
[39] "timeimeBodyGyroscopescopeJerkMagnitudenitude-mean()"                   
[40] "timeimeBodyGyroscopescopeJerkMagnitudenitude-std()"                    
[41] "frequencyrequencyBodyAccelerometerelerometer-mean()-X"                 
[42] "frequencyrequencyBodyAccelerometerelerometer-mean()-Y"                 
[43] "frequencyrequencyBodyAccelerometerelerometer-mean()-Z"                 
[44] "frequencyrequencyBodyAccelerometerelerometer-std()-X"                  
[45] "frequencyrequencyBodyAccelerometerelerometer-std()-Y"                  
[46] "frequencyrequencyBodyAccelerometerelerometer-std()-Z"                  
[47] "frequencyrequencyBodyAccelerometerelerometerJerk-mean()-X"             
[48] "frequencyrequencyBodyAccelerometerelerometerJerk-mean()-Y"             
[49] "frequencyrequencyBodyAccelerometerelerometerJerk-mean()-Z"             
[50] "frequencyrequencyBodyAccelerometerelerometerJerk-std()-X"              
[51] "frequencyrequencyBodyAccelerometerelerometerJerk-std()-Y"              
[52] "frequencyrequencyBodyAccelerometerelerometerJerk-std()-Z"              
[53] "frequencyrequencyBodyGyroscopescope-mean()-X"                          
[54] "frequencyrequencyBodyGyroscopescope-mean()-Y"                          
[55] "frequencyrequencyBodyGyroscopescope-mean()-Z"                          
[56] "frequencyrequencyBodyGyroscopescope-std()-X"                           
[57] "frequencyrequencyBodyGyroscopescope-std()-Y"                           
[58] "frequencyrequencyBodyGyroscopescope-std()-Z"                           
[59] "frequencyrequencyBodyAccelerometerelerometerMagnitudenitude-mean()"    
[60] "frequencyrequencyBodyAccelerometerelerometerMagnitudenitude-std()"     
[61] "frequencyrequencyBodyAccelerometerelerometerJerkMagnitudenitude-mean()"
[62] "frequencyrequencyBodyAccelerometerelerometerJerkMagnitudenitude-std()" 
[63] "frequencyrequencyBodyGyroscopescopeMagnitudenitude-mean()"             
[64] "frequencyrequencyBodyGyroscopescopeMagnitudenitude-std()"              
[65] "frequencyrequencyBodyGyroscopescopeJerkMagnitudenitude-mean()"         
[66] "frequencyrequencyBodyGyroscopescopeJerkMagnitudenitude-std()"          
[67] "subject"                                                               
[68] "activity"    
                                              
# Looking at the names to see if they are more readable (row 61)

# Tidy data set is produced (rows 64 to 67)

