title:  The spelled-out intro to neural networks and backpropagation - building micrograd 
date: 2023-05-02

Autograd - automatic gradient

Chain rule - knowing the instantaneous rate of change of z relative to y and that of y relative to x allows one to calculate the instantanous rate of change of z relative to x as the product of the two rates of change

Interested in derivitive of loss fucntion with respect to weights of neural network

How these weights are impacting the loss function

Backpropogation - recursive application of the chain rule backwards through the computational graph

Neural nets are mathematical expression
- Forward pass
- Loss function
- Prediction
- Backward prop to get gradient
- Update weights to minimize loss
