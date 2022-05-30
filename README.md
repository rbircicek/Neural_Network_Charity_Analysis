#  Neural_Network_Charity_Analysis
# Overview of the Project
Use Machine Learning, ML, and neural networks to determine if the applicants will be successfull when funded by Alphabet Soup. The resource is  a csv file that contains around 34,000 organizations receiving funding from Alphabet Soup. There are three sections in this project:

 - Prerocessing the data
 - Compile, Train and Evaluate the Model
 - Optimize the Model

#  Results
# Preprocessing: 
Target variable here is IS_SUCCESSFULL, because we would like predict focusing on the organizations been successfull. Feature variables are APPLICATION_TYPE and CLASSIFICATION, whereas EIN and NAME are neither of the variables. EIN, Employee Idendifcation Number and Name of the company do not have any impact on being successfull or not. 

# Compilation - Training - Evaluation 

There are two hidden layers in this model, with 80 neurons and 30 neurons, respectively. Both layers use the "relu" activation function, while the ouput layer use the "sigmoid" function.

![image](https://user-images.githubusercontent.com/96134924/171036109-4af4ea3b-ce4d-48e6-9eb3-1ec105cd59f7.png)

# Optimization 
The desired target was 75% for accuracy, which was never reached. The highest level of accuracy was 69.9% during the first attempt.

![image](https://user-images.githubusercontent.com/96134924/171036812-704c8b6f-d9f1-4870-9a7e-c8999ad8d7e1.png)


When an additional hidden layer added, with additional neurons, the accuracy was decreased to 53.7%.

![image](https://user-images.githubusercontent.com/96134924/171045769-688b6e09-9c58-4cfe-96e2-dbb6de89b781.png)

![image](https://user-images.githubusercontent.com/96134924/171045849-401c6cc4-7937-4031-b645-a2dd15726e66.png)

In the final optimization, the activation function for the ouput layer was changed to "tanh" (tangent h), and the accuracy went down to 46.5%.

![image](https://user-images.githubusercontent.com/96134924/171047166-b2a8e412-e6e1-489a-b7a1-567b852db094.png)

![image](https://user-images.githubusercontent.com/96134924/171047208-1f710c86-18aa-440a-9eff-6fb5781e401b.png)


# Summary

The model could not reach to the target accuracy of 75% despite the optimization, but was close to 75% with an accuracy of 69.9% in the first try. The accuracy could get closer to 75%, if more data were provided in the dataset. A better accuracy might have been reached with the Random Forest Classifier because it creates as many trees on the subset of the data and combines the output of all the trees. In this way it reduces overfitting problem in decision trees and also reduces the variance and therefore improves the accuracy. 
