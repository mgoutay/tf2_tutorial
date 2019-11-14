# tf2_tutorial
Here are some slides and a notebook that covers the basic about Tensorflow 2.0.



Here, you will find the PowerPoint presentation, the associated PDF, and the the notebook version of the tutorial. It is also available for you [to try on Google Collab](https://colab.research.google.com/github/mgoutay/tf2_tutorial/blob/master/MNIST_tutorial.ipynb).


The following are discussed :

1. Introduction to Deep Learning
   - What is Deep Learning?
   - Neurons, layers...
   - The training loop : loss function, regularization, SGD.
2. Tensorflow for beginners
   - What's a Tensor, a TF constant & variable
   - Preparing a dataset
   - Building a model with the Sequential API and training it

3. Tensorflow for experts
   - Creating a Tensorflow dataset
   - Defining new layers with the Subclassing API
   - Composing a model from custom layers
4. Building a custom training loop
   - Defining custom training and testing function, and a custom training loop
   - Building a graph with *@tf.function*
   - Adding regularization
   - Building a custom loss function
