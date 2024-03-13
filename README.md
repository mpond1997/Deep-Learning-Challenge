# Deep-Learning-Challenge
Overview of the analysis: 
~ Data from charity organizations, their income and whether or not they were successful in their uses of the money.

Results: Using bulleted lists and images to support your answers, address the following questions:

Data Preprocessing

What variable(s) are the target(s) for your model? 
~APPLICATION TYPE
What variable(s) are the features for your model?
~ IS_SUCCESSFUL
What variable(s) should be removed from the input data because they are neither targets nor features?
~ NAME, EIN
Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why? 
~41 neurons, 3 layers, 5 units for the first two layers. it was the most optimized and adding did not help.
Were you able to achieve the target model performance? 
~No.
What steps did you take in your attempts to increase model performance?
~ Started by transforming more data to get rid of outliers, then extensively tested different amounts of layer, units, etc.
Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
~ Overall results were just short of the 75% successful accuracy, this was after extensive testing of the data. Using different features could be a different way to make this successful as the is_successful only having two possible results makes accuracy tough. If every other one is wrong this can cause massive loss in accuracy.
