# Neural_Network_Charity

## Purpose of Analysis
The purpose of this analysis is to determine which businesses that have received funding from Alphabet Soup have been successful.

## Results
### Target variable: Whether or not the funding was successful
### Input variable: 
APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT, SPECIAL_CONSIDERATIONS
### Which variables should be removed?
EIN and NAME should be removed from the input data
### Model Parameters
Originally the model had 2 hidden layers with 24 and 12 neurons respectively.
To attempt to increase model performance, I added more hidden layers, more neurons per hidden layer, more epochs, or changed up the activation function. (Note: the different attempts at optimization can be seen in seperate commits) Despite all changes, the model never reached the required 75% accuracy. 

### Summary
Overall, the model started off with a peak of 74% accuracy and, despite attempts at optimization, did not go higher than 74.4% accuracy. If this project were to do to achieve better results, it is recommended to try a random forest machine learning model. The random forest model can train and predict on comparitively large datasets in shorter time than deep learning models. Furthermore, the random forest model does not sacrifice accuracy for efficiency; it is just as accurate as a deep learning model, in lesser time. 
