# mnist-tensorflow
Simple notebooks to classify MNIST dataset using TensorFlow

There are two notebooks namely MNIST-CNN and MNIST-DNN in this repository.
MNIST-DNN is a notebook which implements a Fully Connected Layer network to recognize the digits, giving a decent performance of around 97-98 %.
In this I do the task in 2 ways : First using an explicitly defined generic function which generates minibatches and the Second using the next_batch feature of mnist data provided by TensorFlow

MNIST-CNN is a notebook which implements a Convolution Layer - FC Layer - Softmax architecture to recognize the digits. 
Note that this uses the relatively new tf.estimator API.
Also the CNN gives a raltively bad performance of about 95-96 %, but this can be bettered by using better optimization algorithms like Adam instead of Stochastic Gradient Descent, running for more epochs, decreasing dropout probability, adding more layers, etc.
