# digit-classification
- This code uses Tensorflow and keras to train a neural network to classify handwritten digits.
- The popular MNIST dataset is used. It has a training set of 60,000 examples, and a test set of 10,000 examples.
- The images are all 28x28 images
- The neural network takes 784 dimensional vectors as inputs (28 rows * 28 columns) and will output a 10 dimensional vector.
- The output is represented as a 10-dimensional vector using One-hot encoding.
- A Sequential class defined in Keras is used to create the model. All the layers are Dense layers.
- We train the model for 3 epochs.
