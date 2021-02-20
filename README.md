# Neural Network Charity Analysis

## Preview

This project aims to create a deep-learning neural network to analyze, evaluate and help Non-Profit organization AlphabetSoup with its decision-making of which oraganization should receive donations.


## Results

* ### Data Preprocessing
  - Target output or the "y" for this model is "IS_SUCCESSSFUL".
  - All other independent variables are considered to be the features or "X" in this model.
  - "EIN" and "NAME" are neither targets nor features and were removed from the input data. 


* ### Compiling, Training, and Evaluating the model
  - For this model I had two hidden layers. 50 neurons for the first hidden layer and 25 for the second hidden layer. For both hidden layer, "relu" activation were used then "sigmoid" activation for the output layer. 
  - This model with 73% accuracy did not able to achieve the target model performance of 75%. 
  - To achieve the target model perofrmance, "EIN", "NAME" and "USE_CASE" columns were dropped and three modifications were performed.
    
    First Attempt:
    
    The model had two hidden layers. First hidden layers with 60 neurons and second hidden layer with 30 neurons. The model has 73% accuracy.
    
    Second Attempt:
    
    The model had three hidden layers. First hidden layers with 120 neurons, second hidden layer with 60 neurons and the third one has 30 neurons. The model has 73% accuracy.

    Second Attempt:
    
    The model had three hidden layers. First hidden layers with 100 neurons, second hidden layer with 40 neurons and the third one has 20 neurons. The model has 73% accuracy.
   

## Summary 

Initial Neural Network model and optimization fail to achieve the target performance of 75% even with the modification performed. 
