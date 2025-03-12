# deep-learning-challenge
Module 21 Challenge

Report on the Model

Overview of the analysis: Explain the purpose of this analysis.

Results: Using bulleted lists and images to support your answers, address the following questions:

# Data Preprocessing #

1, What variable(s) are the target(s) for your model?

   "IS_SUCCESSFUL"

2, What variable(s) are the features for your model?

   They consist of every alternate column from application_df, obtained by removing the 'IS_SUCCESSFUL' column from the original dataframe.

3, What variable(s) should be removed from the input data because they are neither targets nor features?
   
   The 'EIN' and 'NAME' columns were removed

# Compiling, Training, and Evaluating the Model #

1, How many neurons, layers, and activation functions did you select for your neural network model, and why?
   

2, Were you able to achieve the target model performance?
   
   No, I was unable to.

3, What steps did you take in your attempts to increase model performance?
   

# Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation. #
   72.50% accuracy achieved.
