# Classification-model with deep learning

In this project I will use a dataset from Kaggle. The goal is to predict the survival rate of patients with heart failure from certain factors like age, anemia, diabetes and so on. 

Cardiovascular diseases are the #1 cause of death globally, and it takes 17.9 million lives each year. This accounts for 31% percent of all deaths world wide!

These deaths are avoidable and can be prevented by addressing behavioural risk factors like smoking and an unhealthy diet. People with high risk of cardiovasucalar disease need an early detection and management. This is where the deep learning model comes in. 

## Model 
The model in use is a neural network with:
- one hidden layer with 15 nodes which uses the relu activation function
- an output layer with 2 nodes which uses the softmax activation function

As for the loss function it is going to use categorical crossentropy, and the optimizer in use is Adam 🍎
