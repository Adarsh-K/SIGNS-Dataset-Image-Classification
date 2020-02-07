# SIGNS-Dataset-Image-Classification. The code is in Python.
# There are 2 implementations of the Classifier:
  1. Using ConvNets in Tensorflow
  2. Using ResNets in Keras
  
Note: All the files are well documented and commented wherever I felt necessary

# Using ConvNets in TF-

Run SIGNS Image Classification using ConvNets TF.ipynb file which does the following:
  1. Begin by importing the requirements(See TF Version)
  2. Load the Training and Testing Dataset
  3. Forward Propogartion(For more info see SIGNS Image Classification using ConvNets TF.ipynb under Forward Propogation)
  4. The model which implements a 3 layered ConvNet as: 
    CONV2D -> RELU -> MAXPOOL -> CONV2D -> RELU -> MAXPOOL -> FLATTEN -> FULLYCONNECTED

# Using ResNets in Keras-
Run SIGNS Image Classification using ResNets Keras.ipynb file which does the following:
  1. Implements the Identity Block of our ResNet
  2. Implements the Convolution Block of our ResNet
    (See the model of ResNet in the figure)
  3. Implements the ResNet50 as:
    CONV2D -> BATCHNORM -> RELU -> MAXPOOL -> CONVBLOCK -> IDBLOCK*2 -> CONVBLOCK -> IDBLOCK*3
    -> CONVBLOCK -> IDBLOCK*5 -> CONVBLOCK -> IDBLOCK*2 -> AVGPOOL -> TOPLAYER
  4. Loads the pre-trained model on SIGNS Dataset as it's very computationally heavy to train such a deep network
  5. Test your own image!
  
