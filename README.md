# Module_20_Challenge


### Overview of the analysis: 

#### Explain the purpose of this analysis.

The objective of this analysis is to preprocess this data for neural network model and train, evuluate, and optimize the model. This model will be used to predict whether or not the organization in need of funds will be successful if funded.

### Results: Using bulleted lists and images to support your answers, address the following questions.

#### Data Preprocessing

A list of variables present in the data has been made below. 

EIN and NAME— Identification columns
APPLICATION_TYPE— Alphabet Soup application type
AFFILIATION— Affiliated sector of industry
CLASSIFICATION— Government organization classification
USE_CASE— Use case for funding
ORGANIZATION— Organization type
STATUS— Active status
INCOME_AMT— Income classification
SPECIAL_CONSIDERATIONS— Special consideration for application
ASK_AMT— Funding amount requested
IS_SUCCESSFUL— Was the money used effectively


#### What variable(s) are neither targets nor features, and should be removed from the input data?



### Compiling, Training, and Evaluating the Model

#### How many neurons, layers, and activation functions did you select for your neural network model, and why?

80 nuerons were included in first hidden layer and the 30 nuerons were included in the second hidden layer. Two hiddenn layers were included in the algorithm with the "relu" activation function. The activation function of the output layer was selected as "sigmoid". Both hidden and output layers have "relu" and "sigmoid" activation fuctions. 

#### Were you able to achieve the target model performance?

The model was able to gain accuracy of 72.6% and fell short of the target of 75%

![1](https://user-images.githubusercontent.com/69175360/216482568-86bb744e-c6ba-4470-8451-78cea69d8ea8.JPG)


#### What steps did you take to try and increase model performance?

to improve the accuracy, several changes were made. I dropped the column "SPECIAL_CONSIDERATIONS", changed the number of nuerons in hidden layers to increase the number of variables, added the third hidden layer to improve the accuracy of the method, and changed the activation function of the output layer from "sigmoid" to "tanh".

### Summary: 

#### Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.

The accuracy of the algorithm is below 75% even after making several modifications making this not in the acceptable range.  We can determine that this neural network algorithm does not work well with this data set. 
