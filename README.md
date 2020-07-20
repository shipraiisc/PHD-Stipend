# PHD-Stipend
Data Source: https://www.kaggle.com/paultimothymooney/phd-stipends/data#


1) What is the size of the data set, and was any data excluded?

   Original Data size is 8707 x 11. Records with no values in "University" and "Overall Pay" fields were extracted. 


2) What data cleaning steps did you perform and why?		
  
  converted numeric field to "float" from "object" data type
  Dropped columns with highest null values
  
  
3) Are there any outliers that should be treated separately? And how did you treat them?	

  Outliers of "Overall Pay" were noticed using boxplot. Data points away from quartiles were extracted.
  
  
4) What questions did you ask and what interesting relationships, subsets, or clusters can you find?	


5) How much time did you spend on this?								
