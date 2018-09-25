# DeepNeuralNetwork-Classification

## Overview

This code classfies the clothing and accessories into it's respective category which it learns using the [Zolandoresearch Fashion MNIST dataset](https://github.com/zalandoresearch/fashion-mnist). 
![alt Sample Data from Fashion MNIST](https://github.com/ChanduSharma/DeepNeuralNetwork-Classification/blob/master/Figure_1.png)

This code consist of a 3-layer feed forward network which classifies the images into one of the 10 categories of clothing and accessories defined in the dataset. The input to the neural network is a 28X28 size black and white images and the output is an array of 10 probabilities values corresponding to each class.

|   Set   |  Accuracy |
|---------|-----------|
|  Train  |   98.08%  |
|  Test   |   89.11%  |

## Dependencies

- TensorFlow
- Numpy
- Matplotlib

## DataSet

The data set was taken from the Fashion MNIST repository by zalandoresearch. The training set contains 60,000 examples and the test set contains 10,000 examples. Each example is a 28x28 grayscale image, and has an associated label from 10 classes.

|Target class |	Definition |
|-------------|------------|
| 0	| T-shirt/top |
| 1 |	Trouser |
| 2 |	Pullover |
| 3 |	Dress |
| 4 |	Coat |
| 5 |	Sandal |
| 6 |	Shirt |
| 7 |	Sneaker |
| 8 |	Bag |
| 9 |	Ankle boot |

## Output

The output is a image with predicted label, it's confidence score and true label. The corresponding image is a bar plot representing the confidence of neural network for the predicted label.
![alt Sample Output](https://github.com/ChanduSharma/DeepNeuralNetwork-Classification/blob/master/Figure_2.png)

## Usage
Run `python main.py`
