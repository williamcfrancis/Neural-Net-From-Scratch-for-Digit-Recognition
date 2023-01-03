# Neural Network From Scratch for Digit Recognition
In this project, I implemented a Neural Network from scratch using the numpy library to recognize digits from the MNIST dataset. The backward propagation was implemented by taking the derivative, rather than using a pre-defined backward function from a library such as Pytorch, Keras, or TensorFlow. I also designed the forward and backward propagation functions for the softmax cross entropy loss.

To evaluate the performance of the Neural Network, I trained it on the MNIST dataset and obtained the following results:

![train](training.PNG)

![val](val1.PNG)

![val](val2.PNG)

In addition, I implemented a second Neural Network using Pytorch and compared its performance to the one implemented from scratch. The results showed that both Neural Networks achieved high accuracy on the MNIST dataset:

![pyt](pyt1.PNG)

![pyt](pytorch2.PNG)

Overall, this project has allowed me to strengthen my understanding of Neural Network principles and gain experience in implementing them effectively without relying on existing libraries.
