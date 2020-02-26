
Deep Neural Networks for Fashion Mnist Classification

1-Build Deep Neural Network with different activation functions , Adam optimization and early stoping technique
Early stopping is a technique for controlling overfitting in machine learning models, especially neural networks, by stopping training before the weights have converged. Often we stop when the performance has stopped improving on a held-out validation set (stop training at the point when performance on a validation dataset starts to degrade)


2-Load the pretrained model from question 1:(A), freeze all layers and replace the softmax layer with a new one to classify images with classes from 5 to 9. Use Adam optimizer and train it for 30 epoch with

a- All layer freezing

b- With unfreezing the last two hidden layers from the pretrained model
