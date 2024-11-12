# Neural Network Hyperparameters Experiment
Hyperparamters are the parameters inside a neural network that the user building the neural network can change or manipulate to produce the most accurate prediction.

Here, in our experiment with hyperparameters, we are taking a Neural network for Digit classification and comparing it's accuracy and loss values versus the varying Hyperparameters

## Dataset
Here, we have used the popular MNIST dataset which contains handwritten digits consisting of 60,000 training set and a test set of 10,000 images of 28x28 pixels.


![MNIST Dataset](https://upload.wikimedia.org/wikipedia/commons/f/f7/MnistExamplesModified.png "a title")


## List of Hyperparamters to be tested
1) Epochs = [10,20,30,50]
2) Batch size = [28,64,128,256,512]
3) Learning Rate = [0.001,0.01,0.1,0.5,0.9]
4) Optimizers = [SGD,Adam,RMSprop,Adagrad]

## Approach while conducting this experiment
Changing all the hyperparameters at the same time would create intricate graphs and not really give us the impact that each hyperparameter has on the model.so firstly we will create a base model on top of which we will vary the respective hyperparameters

1) Create a base model with fixed hyperparameters
2) Experiment 1- Varying Learning Rate
3) Experiment 2- Varying Batch SIze
3) Experiment 3- Varying Epoch Count
5) Experiment 4- Varying Optimizing Algorithm

## Experiment-1(Varying Learning rate)
In the first experiment we vary learing rates [0.001,0.01,0.1,0.5,0.9] and loop through each learning rate to obtain it's accuracy and average loss.The curve obtained are as follows
 

![alt](<results/plots/Learning Rate vs Accuracy.png>)

![alt](<results/plots/Learning Rate vs Average Loss.png>)
 

## Experiment-2(Varying Batch Sizes)
Here in the second experiment we vary Batch size [28,64,128,256,512] and loop through each learning rate to obtain it's accuracy and average loss. The curve obtained are as follows
 

![alt](<results/plots/Batch Sizes vs Accuracy.png>)


![alt](<results/plots/Batch Sizes vs Average Loss.png>)


## Experiment-3(Varying Optimizers)
Here in the second experiment we vary optimizers [SGD,Adam,RMSprop,Adagrad] and loop through each learning rate to obtain it's accuracy and average loss. The curve obtained are as follows
 

![alt](<results/plots/Optimizer vs Accuracy.png>)


![alt](<results/plots/Optimizer vs Average Loss.png>)


## Experiment-4(Varying Epoch Count )
Here in the second experiment we vary Epoch Counts [10,20,30,50]  and loop through each learning rate to obtain it's accuracy and average loss. The curve obtained are as follows


![alt](<results/plots/Epochs count vs Accuracy.png>)


![alt](<results/plots/Epochs count vs Average loss.png>)