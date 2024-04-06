# number_classifier
Detection of handwritten numbers. 
This is code detects handwritten numbers from an 60000 training examples and 10000 test examples. 
Uses sparse categorical crossentropy as loss function. 
For stochastic gradient descent it uses adam optimization.
The neural network has 3 layers, input layer, hidden layer and output layer.
The nerual network primarily ran on 2 layers and later 3 layers were implemented to increase accuracy from 92% to 97%.
The hidden layer has been run twice first with 100 neurons and later with 1000 neurons to increase accuracy from 97% to 98%.
The code can be used with changed number of hidden layers, type of loss function and stochastic gradient descent for further accuracy.
