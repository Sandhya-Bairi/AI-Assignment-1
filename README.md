# AI-Assignment-1

This assignment shows the classification of MNIST dataset using feed-forward ANN using Keras.

In order to run the available code, the following python libraries are required: Keras, numpy, matplotlib.

The model contains two hidden layers which use relu activation function each followed by dropout of value 0.5 to reduce overfitting.

The output layer uses softmax activation funtion. The optimizer used is adam and loss function is Categorical Crossentropy. 

![1](https://user-images.githubusercontent.com/22190738/36728551-1eab4c52-1be7-11e8-9d58-e027a130cea2.png)

The model is run for 50 epochs and the final accurcy is 98.7% with baseline error of 1.3%.

Relevant graphs are below. 

![1](https://user-images.githubusercontent.com/22190738/36728897-5730f8e6-1be8-11e8-93bd-366d67482e2a.png)


![2](https://user-images.githubusercontent.com/22190738/36728906-5c58e05e-1be8-11e8-8a46-c6b4747ad50b.png)
