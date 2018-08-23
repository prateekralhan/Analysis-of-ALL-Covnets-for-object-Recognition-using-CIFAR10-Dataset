# Analysis-of-ALL-Covnets-for-object-Recognition-using-CIFAR10-Dataset

This project mainly deals with the analysis of the ALL-Covnets that were designed in 2015, that is mainly for achieving 
state-of-the-Art performance for object recognition. Here, I have done some manipulations and validations on the 
network and used the Popular CIFAR10 Dataset using Keras, a high-level open source neural network library written in Python, 
that has both tensorflow and theano as its backends.

Here, We import data using Keras, use one-hot vectors for categorical labels and add layers to the model made using keras.
Then, we pre-train weights and make certain predictions using pre-trained keras model.

The CIFAR10 Dataset being used has 60000 images of 32x32 pixels in 10 classes out of which 50000 are used for training 
and the remaining 10 are used for testing.

The python code (.ipynb) needs a Jupyter notebook to run in the system, that can be installed using:
pip install jupter notebook

For further documentation, refer this: http://jupyter.org/install
