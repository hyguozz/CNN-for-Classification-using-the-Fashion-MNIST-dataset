# CNN-for-Classification-using-the-Fashion-MNIST-dataset
Designing a custom convolutional network and evaluating its performance for image classi cation with the Fashion-MNIST or CIFAR 10 dataset.
Convolutional Networks

Implement the example LeNet-5 convolutional neural network to perform image classification with the fashion mnist dataset. Make a series of modifications as described below.

## 1. Baseline network:
You can start with a LeNet-5 style architecture that we discussed in the lecture. As a baseline start
with ReLU activations for the hidden layers, and a softmax output layer.
## 2. Add L2 weight decay regularization:
Add an L2-norm penalty on the weights of your baseline model as regularization. Test two di erent
regularization strengths.
## 3. Add L1 weight decay regularization:
Add an L1-norm penalty on the weights of your baseline model as regularization. Test two di erent
regularization strengths.
## 4. Remove fully-connected layers:
Modify the architecture to remove the fully-connected layers at the backend of the network. For
example, replace with Global Average Pooling or an alternative. Report the change in the number
of parameters for this model compared to previous.
## 5. Analyze the accuracy of the di erent models:
For all six models, train/test your model three times to get a sense of the consistency of the test error.
Keep other aspects of your model the same among designs (# epochs, mini-batch size, hyperparame-
ters). Generate a table that summarizes the training error, test error, standard deviation of test error
across three runs, inference time, and # of parameters for each model.

## 6. Analyze the weights of the regularized models :
For the baseline model and the four regularized models (from parts 2 and 3: L2 and L1 regularization
with two di erent strengths each) measure the sparsity of the weights in each FC layer and create
a bar chart that compares the sparsity between the models in each layer. There are a number of
metrics that measure sparsity, e.g. Hoyer's index. see Table I in https://arxiv.org/abs/0811.4706
