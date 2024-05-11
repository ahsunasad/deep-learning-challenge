# deep-learning-challenge
Code is in the .ipynb file. The report is written below as part of this README file.
Help was used by ChatGPT and the XPert Learning Assistant for writing the code. 

REPORT IS BELOW:

**Overview of the analysis:**
The purpose of this analysis and creating this model is to help the nonprofit foundation Alphabet Soup create a tool that predicts applicants with the best chance of success. The goal of this model is to have at least 75% accuracy with its predictions.  

**Data Preprocessing  Questions:**

**Question 1: What variable(s) are the target(s) for your model?**
The 'IS_SUCCESSFUL' column column from the application dataframe is the target variable.

**Question 2: What variable(s) are the features for your model?**
All other columns of the application dataframe are part of the feature variables. 

**Question 3: What variable(s) should be removed from the input data because they are neither targets nor features?**
The variables that should be removed from the input data because they're neither target/feature variables are 'NAME' and 'EIN'. This is why these variables were dropped.

**Compiling, Training, and Evaluating the Model Questions:**

**Question 4: How many neurons, layers, and activation functions did you select for your neural network model, and why?**
I selected 10 'hidden_nodes_1' (first layer) and 5 'hidden_nodes_2' (second layer) for my neural network model. I thought it would be interesting to see what the results would look like with double 'hidden_nodes_1' compared to 'hidden_nodes_2'.

**Question 5: Were you able to achieve the target model performance?**
it was close, but I was not able to achieve the target model performance of 75%. Although I did achieve 74.17% accuracy, so I was very close with my first attempt. 

**Question 6: What steps did you take in your attempts to increase model performance?**
To increase model performance I would add more layers, more nodes, and remove more unnecessary columns. 

**Summary of the overall results of the model:**
In summary, I achieved about 74.17% accuracy. This was very close to the target model performance of 75%, which showed that I was on the right track. I could realistically achieve over 75% accuracy witha  few changes I will highlight in the next section.

**How I could use a different model:**
I could use a slightly different model to solve the same problem, in order to push my accuracy above the 75% goal. I could do more cleanup of my data by ensuring unecessary data/columns are removed. I could also use a model with more layers/nodes. Finally, I could attempt to use a model with higher correlation between input vs. output to increase final accuracy.
