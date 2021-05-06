### What is a neural network neuron?
Neurons are the basic fundamental building blocks of a neural network. A neuron in NN,receives input from other neurons and produces an output. 
![image](https://user-images.githubusercontent.com/16747373/117242668-56665e00-ae53-11eb-905f-84156b5e047f.png)

Here, there 2 are inputs to the neuron, f(X) represents the processing done on the inputs and y represents the output of the neuron.

### What is the use of the learning rate?
Neural Networks are trained using an algorithm called  stochastic gradient descent known as SGD which optimizes or reduces the error occured by comparing the output obtained from the training set and the actual weight. Then based on the error condition, the weights are updated accordingly using the technique known as backpropagation.The amount that the weights are updated during training is referred to as the step size or the “learning rate.” Normally this value will be a small value that ranges between (0,1). Based on the learning rate, the model will be trained faster or slower. The smaller the value of learning rate, the training will be slower. If the learning rate is higher then the model converge too quickly and might not give the best result.

### How are weights initialized?

In deep learning, the goal is to find the optimum weights of the model to get the desired output. In transfer learning, the network is initialized using the best pre-trained weights. There are different techniques to initialize weights in NN. Some of the techniques are 
* Uniform distribution:    
        Choosing high values of weights is not the best for the model as it brings problems of exploding and vanishing gradients. The general way to initialize weights is to select small random values, which are close to 0. Good practice is to start your weights in the range of [-u,u] where u is sqrt(1/n) where n is number of inputs to neurons.
* Normal distribution
        Another way is to initialize weights randomly from a normal distribution. As most values are concentrated towards the mean, most of the random values selected have higher probability to be closer to mean (say mean=0)
Other advanced techniques include
1.  Xavier Weight Initialization
2.  He Weight Initialization

### What is "loss" in a neural network?
Loss is the quantitative measure of deviation or difference between the predicted output and the actual output in anticipation. It gives us the measure of mistakes made by the network in predicting the output.And the method to calculate the loss is called Loss Function.There are various loss functions options we have, namely, Mean Squared Error Loss, Binary CrossEntropy Loss, CrossEntropy Loss, Absolute Error Loss, Huber Loss etc.


### What is the "chain rule" in gradient flow?
![image](https://user-images.githubusercontent.com/16747373/117249606-7e5bbe80-ae5f-11eb-8933-2f6b7d6d8869.png)****













