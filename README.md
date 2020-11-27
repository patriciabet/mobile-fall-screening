**Mobile inertial sensors and fall risk prediction in community-dwelling elderly**

----------------------------------------------------------------------------------

Python functions to manipulate gait data from TUG tests

Author: Patricia Bet and Moacir A. Ponti 
-> in collaboration with: Paula Castro

There are two types of files in this repository:

1. Code:

- gaitAnalysis.py : contains several functions to 
                    read csv files with accelerometer data
		    and performing feature extraction

2. Object files:

- data_accelerometer.pkl: python object containing all the 
		          accelerometer data with anonymize IDs

- featuresAcc.npy: python object containing all the 
                   accelerometer features with anonymize IDs 



This repository was made public in order to allow for
      reproducibility of the results reported in the paper:

   P. Bet, P.C. Castro and M. Ponti
   "Foreseeing future falls with accelerometer features 
   in active community-dwelling older persons 
   with no recent history of falls"

   the paper is currently published at Experimental Gerontology
   link:
   https://www.sciencedirect.com/science/article/pii/S0531556520304873
       
   the following citation must be used when using the code or data from this study:
   Bet, Patricia, Paula C. Castro, and Moacir A. Ponti. "Foreseeing future 
   falls with accelerometer features in active community-dwelling older 
   persons with no recent history of falls." Experimental Gerontology (2020): 111139.
      
   paper abstract:
   
   Background:
   Acceleration sensors are a viable option for monitoring gait 
   patterns and its application on monitoring falls and risk of falling. 
   However the literature still lacks prospective studies to investigate 
   such risk before the occurrence of falls.
   Objective:
   To investigate features extracted from accelerometer signals with 
   the purpose of predicting future falls in individuals with no recent history of falls.
   Methods:
   In this study we investigate the risk of fall in active and healthy community-dwelling 
   living older persons with no recent history of falls, using a single accelerometer and 
   variants of the Timed Up and Go (TUG) test. A prospective study was conducted with 
   74 healthy non-fallers older persons. After collecting acceleration data from the 
   participants at the baseline, the occurrence of falls (outcome) was monitored quarterly 
   during one year. A set of frequency features were extracted from the signal and their 
   ability to predict falls was evaluated.
   Results:
   The best individual feature result shows an accuracy of 0.75, sensitivity of 0.71 and 
   specificity of 0.76. A fusion of the three best features increases the sensitivity to 
   0.86. On the other hand, the cut-off points of the TUG seconds, often used to assess 
   fall risk, did not demonstrate adequate sensitivity.
   Conclusion:
   The results confirms previous evidence that accelerometer features can better estimate 
   fall risk, and support potential applications that try to infer falls risk in less 
   restricted scenarios, even in a sample stratified by age and gender composed of active 
   and healthy community-dwelling living older persons.





