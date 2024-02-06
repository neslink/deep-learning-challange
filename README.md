# deep-learning-challange

Module 21 Challange

# Overview 

The purpose of this challange is to develop a Deep Learning model to analyze problems related to classification. 
We will use various features to manipulate a given dataset and utilize it to predict a target variable.

# # Results

Target Variable for our model:

- The target variable for the model is "IS_SUCCESSSFUL". Features for the Model:
- The features for the model include: 1. APPLICATION_TYPE 2. AFFILIATION 3. CLASSIFICATION 4. USE_CASE 5. ORGANIZATION 6. STATUS 8. INCOME_AMT 9. SPECIAL_CONSIDERATIONS 10. ASK_AMT

We removed variables such as [list removed variables] since they don't contribute to the target and dont serve as features for our model.
The variables EIN and NAME were removed from the input data as they are identification columns

# Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?

- The neural network model has three layers: two hidden layers with 5 and 3 neurons, respectively, and an output layer with 1 neuron.
Activation functions used:
Hidden layers: Tanh activation functions were chosen to introduce non-linearity.
Output layer: Sigmoid activation function to produce binary classification probabilities.

- Were you able to achieve the target model performance?
- The model was able to achieve - loss: 0.5510 - accuracy: 0.7353 - 318ms/epoch - 1ms/step Loss: 0.5509999394416809, Accuracy: 0.735276997089386 close to the target performance, indicating its effectiveness in classification tasks.

# Target model performace was 74%

What steps did you take in your attempts to increase model performance?

Our model was trained with default architecture and parameters. To improve our performance other techniques could have been deployed, such as hyperparameters tuning, feature engineering, data augmentation, Random Forest and Gradient Boosting.
Number of neurons in hidden layers was adjusted to observe the impact on performance.
Activation functions were chosen to introduce non-linearity and capture complex relationships.

# Summary

Our deep learning model demostrated positive results in terms of classification of tasks. For further enhancements or improvements, different models such as concolutional neural network could be deployed. Depending on the nature of datasets and questions at hand, exploring different models is crucial for reaching optimal and higher quality performance.