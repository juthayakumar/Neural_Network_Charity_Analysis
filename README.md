# Neural_Network_Charity_Analysis
## Overview
  The purpose of this challenge was to use the features provided in the dataset to predict whether applicants will be succesful if funded by Alphabet Soup.
## Results
  Data Preprocessing
  * The variable considered the target for my model is the IS_SUCCESSFUL column.
  * The variables considered to be the features of my model are columns besides the successful column and ones that will be dropped
  * Variables that are neither targets nor features were the ones I dropped - EIN, NAME, and then afterwards ORGANIZATION.
  
  Compiling, Training, and Evaluating the Model
  * I selected 2 hidden layers, first with 80 neurons and second with 30. The 2 hidden layers have the 'relu' activation function, and the output layer activation function is 'sigmoid'.
  ![image](https://user-images.githubusercontent.com/100812515/179371870-f20d9b09-8306-4bf4-8d6e-c9cd512be1cd.png)

  * I was not able to achieve the target model performance, which is 75%.
  ![image](https://user-images.githubusercontent.com/100812515/179371901-cf83ebba-2554-4c3b-b732-14b2cf87338e.png)
  
  * 3 different attempts were taken to try and increase model performance. The attempts were to drop a column, add an additional hidden layer, and use a different activation function. None of the attempts yeilded a better model performance.
  ![image](https://user-images.githubusercontent.com/100812515/179372079-27520c92-1bab-4191-afd4-268aa1c4bf3e.png)
![image](https://user-images.githubusercontent.com/100812515/179372081-ea07365f-538d-4d15-9a51-fb0462f19c93.png)
![image](https://user-images.githubusercontent.com/100812515/179372085-3aeaaab2-f62b-47ec-a1da-d8403db13273.png)

## Summary
  The overall results showed that the original attempt, along with the modified versions did not meet the accuracy of 75%. The original model was 69% which was close, but not enough. We could use Random forest classifiers next time because it is a more accurate model, and it's our accuracy that is not enough. Another way to create more accuracy could be to remove more columns, or add more layers. 
