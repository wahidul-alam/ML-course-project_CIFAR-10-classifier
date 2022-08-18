# ML_course_project_CIFAR-10-classifier
## Dataset: 
[CIFAR 10](https://www.cs.toronto.edu/~kriz/cifar.html ) dataset with 60000 32x32 color images with 10 classes. 
## part 1: classification using support vector machines
The main tasks are to experiment with different parameters of the model to improve classification accuracy. Experiment and determine the best choices for each of the following. 
1. Best set of image features for color images.
2. Best kernel function (e.g. polynomial, radial basis function) for support vector classification. 
3. Good normalization strategies for the data to yield improved performance. 

### Results:
Training accuracy: 93.5% <br> Testing accuracy: 61.1%

## part 2: Classsification using deep neural networks
Select best set of design parameters for a CNN based multi-class classifier by training and testing on MNIST dataset, a smaller dataset. Following steps to complete as searching for best design parameters:
1. **_Learning rate (LR) and Optimizer: Adam or SGD_**:<br>
  Find proper learning rate for Adam or SGD,  plot training loss vs training epoch number, and compare the      convergence speed of the two optimizers and   their respective test classification accuracies.
2.  **_Activation functions_**:<br>
   Train two networks  with Sigmoid and Relu as respective activation functions. Test and compare the training convergence speeds and classification 
   accuracies on the test dataset. Give your observation.
3.  **_Early stopping strategy_**:<br>
  Develop early stopping strategy. Test the classification accuracies with or without early stopping 
4.  **_Data augmentation_**:<br>
    Augment the training data and train the network. Test the classification accuracy and compare it to that without using augmentation.
5. **_Network depth vs network width_**:<br>
    Design two networks with different depths, but similar total number of parameters. Test the classification accuracy.
Once best set of parameters identified, translate the model to the CIFAR-10 dataset.
### Results:
Training accuracy: 96.11% <br> Testing accuracy: 92.39%
