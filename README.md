# deep-learning-challenge

REPORT :
Explain the purpose of this analysis.

The purpose of this analysis is to create a tool for the nonprofit foundation, Alphabet Soup, that can help it select applicants for funding with the best chance of success in their ventures.

- What variable(s) are the target(s) for your model?
The target variable is the 'IS_SUCCESSFUL' column 
- What variable(s) are the features for your model?
The feature variables are every other column from application_df 
- What variable(s) should be removed from the input data because they are neither targets nor features?
I REMOVED 'EIN' AND 'NAME' because they're neuther targets nor features

- How many neurons, layers, and activation functions did you select for your neural network model, and why?
I added 3 layers and had varying units within them. I tried to change up the activation functions if maybe another function works best with the data set than relu.
I started out with 2 layers and I thought by adding 1 more I would get more accurate results.

- Were you able to achieve the target model performance?
no
What steps did you take in your attempts to increase model performance?
adding a layer, changing the units (hidden_nodes_layer) and changing activation 
