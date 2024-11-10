# Neural Network Hyperparameters Experiment
Hyperparamters are the parameters inside a neural network that the user building the neural network can change or manipulate to produce the most accurate prediction.

Here, in our experiment with hyperparameters, we are taking a Neural network for Digit classification and comparing it's accuracy and loss values versus the varying Hyperparameters

## Dataset
Here, we have used the popular MNIST dataset which contains handwritten digits consisting of 60,000 training set and a test set of 10,000 images of 28x28 pixels.


![MNIST Dataset](https://upload.wikimedia.org/wikipedia/commons/f/f7/MnistExamplesModified.png "a title")


## List of Hyperparamters to be tested
1) Epochs = [10,50,100,200,500,1000]
2) Batch size = [28,64,128.256,512]
3) Learning Rate = [0.001,0.01,0.1,0.5,1]
4) Optimizers = [SGD,Adam,RMSprop,Adagrad]

## Approach while conducting this experiment
Changing all the hyperparameters at the same time would create intricate graphs and not really give us the impact that each hyperparameter has on the model.so firstly we will create a base model on top of which we will vary the respective hyperparameters

1) Create a base model with fixed hyperparameters
2) Experiment 1- Varying Epoch count
3) Experiment 2- Varying Batch size
4) Experiment 3- Varying Learning Rate
5) Experiment 4- Varying Optimizing Algorithm
