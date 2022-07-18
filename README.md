# Neural_Network_Charity_Analysis
## Overview of the analysis:


## Results: 
### Data Preprocessing

- What variable(s) are considered the target(s) for your model?
Checking to see if the target is marked as successful in the DataFrame, displays either the number '1' or '0' to denote 'yes' or 'no' in reference to the probability of the organization being successful if funded by Alphabet Soup Foundation.
![image](https://user-images.githubusercontent.com/97486216/179437259-97c682f4-22ef-4410-9000-34a82d70a070.png)

- What variable(s) are considered to be the features for your model?
The columns of the dataset are considered the features for this model.
![image](https://user-images.githubusercontent.com/97486216/179437531-a210efad-437a-40c7-84e1-d9803e1313a1.png)

- What variable(s) are neither targets nor features, and should be removed from the input data?
Two columns were removed from the model, 'EIN' and 'NAME' because the information they provided is not essential for predicting success of future funding.
![image](https://user-images.githubusercontent.com/97486216/179437763-94197ff7-cc7d-4650-bba5-a5d329cfc129.png)

### Compiling, Training, and Evaluating the Model

- How many neurons, layers, and activation functions did you select for your neural network model, and why?
The first phase utilized two hidden layers and one outer layer. The neurons were arranged with 80 in the first layer, 30 in the second layer, and 1 in the third layer. Three activation functions were used in the first phase: 'relu', 'sigmoid', and 'linear'. The training epochs was set at 10.
![image](https://user-images.githubusercontent.com/97486216/179438861-bee85f42-f1a7-402d-be6c-57b37f63393c.png)

- Were you able to achieve the target model performance?
I was not able to achieve the target model preformance in the first phase. The highest accuracy evaluated by the model was 0.711
![image](https://user-images.githubusercontent.com/97486216/179439553-86a8a010-070c-4d32-9b4b-d090261c6d5f.png)


- What steps did you take to try and increase model performance?
Added more hidden layers. Reduced the number of neurons, increased the epochs, and used the same activation function for every layer. Which increased the model performance to 0.73. Even with multiple changes of hidden layers, numbers of neorons and epochs, I was still not able to  create results that increased the performance to reach .75.
![image](https://user-images.githubusercontent.com/97486216/179440053-5a6a1963-9240-431e-a9bc-eb4d60abbe33.png)

## Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.
