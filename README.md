# Neural_Network_Charity_Analysis

# Overview of the Analysis: 

The purpose of this analysis was to develop a binary classifier that is capable of predicting whether applicants will be successful or not, if funded by Alphabet Soup. From Alphabet Soup’s business team, I have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization that I have used to develop a machine learning model using neural networks. 

# Results: 

  •	Data Reprocessing
      o	Target Variable: IS_SUCCESSFUL
      o	Featured Variables: 'APPLICATION_TYPE', 'AFFILIATION',  'CLASSIFICATION', 'USE_CASE',  'ORGANIZATION', 'INCOME_AMT', 'SPECIAL_CONSIDERATIONS'
      o	Removed Variables: EIN and NAME

  •	Compiling, Training and Evaluating the Model
      o	For my first neural network, I included two hidden layers, in addition to the output layer.
      o	The accuracy of my model is 68.55% so it did not hit the targeted 75%.
      o	To increase the performance of my model, I dropped ASK_AMT from variables and I added an extra layer. However, it decreased the accuracy to 56.36%.  

# Summary: 

My initial neural network machine learning model had an accuracy of 68.55%. Removing more variables and adding more neurons could help increase the accuracy of the model for the future. 

