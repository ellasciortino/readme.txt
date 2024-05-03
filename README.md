# readme.txt
bcog200 final project


Update: 

Please download the csv file under the project repository. The data in that file will be used to pring out various graphs!

Please update the path in the main function to match your computers path to the file. 

1) My breif project description: 
  Objective: I want to take behavioral data (False Alarm rates, Correct Rejections, HITs, Misses, and Trial count) to find the individual threshold for each rodent. This should be useful in behavioral detection paradigms, to figure out when the rodent can accurately percieve a stimulus (ie. auditory tone, tactile stimuli, smell etc.) I plan to have the user imput the behavioral data listed above. Implement an algorith that will take that data and output the animals threshold data to the user. 


2) Potential functions:
  2a.) Prompt_user() : This function will prompt the user to input the various behavioral data metrics. The input value will be none and the output will be a dictionary of the various user input values.
  2b.) Calculate_d_prime(hit_rate, false_alarm_rate) : This function will use the hit_rate and false_alarm rate data to calculate that animals sensitivity to the stimulus or d'. Returns d'.
  2c.) Calculate_criterion(hit_rate, false_alarm_rate) : This function will impliment an algorithm to deicfer the personal bias for that rodent and what the strength of the stimulus needs to be in order to respond. It will find the z score for both false_alarm and hit_rate values. returns c.
   
  
