# Deep_learning_practice
These are the implement of some deep learning related algorithm based on tensorflow
1)The description of this project:
In this project,  you will implement a CNN for CIFAR-10 dataset.  The image dataset contains 60k  32x32 color images of objects 
of 10 classes as shown below. Further information on the dataset can be found in http://www.cs.toronto.edu/~kriz/cifar.html
See the attached instructions on the architecture of the CNN. 

2)You are required to implement the CNN completely using Tensorflow’s native functions to specify the CNN structure and to 
perform its training.   You will be given 50,000  images (5000 images for each class) for training and 5000 images 
(500 image for each class)  for testing.  Like previous assignment, we will withhold 5000 images to evaluate your program. 
Perform the following tasks

1.	Give the dimension for each layer, and the number of weight parameters for each convolutional layer and the output layer 

2.	Implement in Tensorflow the back-propagation method to train the CNN.  Initialize weights for all filters for the convolutional 
layers to small values and iteratively update them with appropriate learning rate until convergence.  Plot the training and testing
errors for each epoch.  Save weights for all layers, as detailed in the attached instructions.

3.	Visualize the learnt filters for the first convolution layer (see attached instructions).

4.	Given the trained CNN, evaluate its performance on the testing dataset by computing its classification error for each class 
as well as the average classification errors for all 10 classes.  

Submit your Tensorflow code via LMS, along with the required plots, final classification accuracy for the testing data, filter
images for layer 1, and the saved weights.Further information on the dataset, the architecture of the CNN, and on Tensorflow implementation details can be found 
in the attached instructions.
