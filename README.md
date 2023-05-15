# deep-learning-challange

The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organisations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organisation, such as:

EIN and NAME—Identification columns

APPLICATION_TYPE—Alphabet Soup application type

AFFILIATION—Affiliated sector of industry

CLASSIFICATION—Government organisation classification

USE_CASE—Use case for funding

ORGANIZATION—Organisation type

STATUS—Active status

INCOME_AMT—Income classification

SPECIAL_CONSIDERATIONS—Special considerations for application

ASK_AMT—Funding amount requested

IS_SUCCESSFUL—Was the money used effectively





#Optimization: Attempt 1

APPLICATION_TYPE cutoff = 500

CLASSIFICATION cutoff = 300

layer1 = 8

layer2 = 30

Loss: 0.5537382960319519,
Accuracy:  0.7293294668197632

A loss value of 55 indicates that the model can be further optimized.

The accuracy percent shows that 72.9% of the model's predicted values align with the true values in the original dataset.



#Optimization: Attempt 2

APPLICATION_TYPE cutoff = 500

CLASSIFICATION cutoff = 300

layer1 = 12

layer2 = 24

Loss:  0.553446888923645
Accuracy:  0.7279300093650818

A loss value of 55 indicates that the model can be further optimized.

The accuracy percent shows that 72.7% of the model's predicted values align with the true values in the original dataset.




#Optimization: Attempt 3

APPLICATION_TYPE cutoff = 500

CLASSIFICATION cutoff = 300

layer1 = 18

layer2 = 36

Loss: 0.5551065802574158
Accuracy:  0.7290962338447571

In the three attempts,the model was unable to achieve a target predictive accuracy higher than 72.9%.










