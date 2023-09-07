# project2
In this project, dataset from kaggle was explored. The original dataset contained information on 3 million used cars but in this project the dataset was modified to contain information on 426K cars to ensure speed of processing. The goal of this analysis is to understand what factors make a car more or less expensive and consequently provide clear recommendations to your client -- a used car dealership -- as to what consumers value in a used car.

The different models were built and evaluated: 
  Model#1 : Linear Regression
  Model#2 : Ridge
  Model#3 : SequentialFeatureSelection using the Lasso to select 6 features

Based on each model evaluation (MSE) the final selected model was: Ridge

Conclusion and Recommendations:

My client inventory should reflect the above results. Client is advised to have car inventory with the following featires:

- Majority with Gas fuel type cars
- SUV, trucks, sedan and pick-ups are the most wanted cars
- Low mileage
- Finally, advised to stack cars from the following manufacturers: Ford, Chevrolet, and Toyota

Full details can be found at jupyter notebook located @: https://github.com/malkhairy/project2/blob/afde330df45fb35c4e22b0190f8ed989cf89f1ff/prompt_II.ipynb
