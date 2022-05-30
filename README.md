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

