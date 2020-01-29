# CNN-model-for-hand-sign-image-recognition-using-Tensorflow-deeplearning.ai-coursera

- In this assignment I Built and trained a ConvNet in TensorFlow for a classification problem. The problem was to classify the
hand signs of numbers into that numbers. The dataset in this problem is a collection of 6 signs made by hand representing numbers
from 0 to 5.
- In this model I implemented helper functions create_placeholders(), initialize_parameters() using Xavier Initialization, 
forward_propagation(), compute_cost() that will be used when implementing the model() function.
- I initialized the parameters using Xavier Initialization and optimized using Adam Optimizer for each mini batch and used 
cross entropy loss function.
- The architecture of the CNN is CONV2D -> RELU -> MAXPOOL -> CONV2D -> RELU -> MAXPOOL -> FLATTEN -> FULLYCONNECTED.
- Train Accuracy = 0.94 and Test Accuracy = 0.78
