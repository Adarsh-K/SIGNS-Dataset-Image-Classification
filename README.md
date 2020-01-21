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
  4. The model which implements a 3 layered ConvNet as: CONV2D -> RELU -> MAXPOOL -> CONV2D -> RELU -> MAXPOOL -> FLATTEN ->        FULLYCONNECTED
