# VanillaCNN

### What is this project?
This project implements a CNN that classifies handwritten digits from the MNIST dataset using only numpy.

### Why?
Currently, while there are a lot of materials on Convoluational Neural Networks available online, to my knowledge, none of them concretely derives how CNNs work and then implements a CNN using their derivation. This project aims to **concretely derives the math** behind Convolutional Neural Networks and then **implements an instance** of CNN using this derivation.

Read the paper [here](https://github.com/nganvu/VanillaCNN/blob/master/paper.pdf)! (Updated 12/12/2018)

### How?
To run my implementation:
```
./vanilla_cnn
```

To run the Keras equivalence:
```
./keras_cnn
```

Look, the loss is actually decreasing!

<img src="https://github.com/nganvu/VanillaCNN/blob/master/screenshot.png" width="360">

### To-dos
* Parallelize the computation of individual training data points, as they are completely independent of one another.
* Replace the sigmoid function in the Fully Connected Layer with the softmax function, which is often used for categorical predictions like with MNIST.
* Implement better variations of gradient descent (e.g. incorporating momentum, adjusting learning rate over time, etc.)
* Write unit tests to ensure each mathematical operation was implemented correctly.
