MITx 6.86x
Machine Learning with Python-From Linear Models to Deep Learning

Project 1

The goal of this project was to design a classifier to use for sentiment analysis of product reviews. The training set consists of reviews written by Amazon customers for various food products. The reviews, originally given on a 5 point scale, have been adjusted to a +1 or -1 scale, representing a positive or negative review, respectively.

I implemented the hinge loss functions and compare three types of linear classifiers: the perceptron algorithm, the average perceptron algorithm and the Pegasos algorithm. Aditionally, implemented a classification function that uses  θ  and  θ0  to classify a set of data points into -1s and 1s prediction greater than zero - positive classification). Finally, with the classifier_accuracy I train the given classifier using the training data and then compute compute the classification accuracy on both the train and validation data. The return values are a tuple where the first value is the training accuracy and the second value is the validation accuracy.


Files description:

project1.py contains various useful functions and function to implement your learning algorithms.

main.py is a script skeleton where these functions are called to run the experiments.

utils.py contains utility functions that the staff has implemented.

test.py is a script which runs tests on a few of the methods you will implement.

Data
The data consists of several reviews, each of which has been labeled with  −1  or  +1 , corresponding to a negative or positive review, respectively. The original data has been split into four files:

reviews_train.tsv (4000 examples)
reviews_validation.tsv (500 examples)
reviews_test.tsv (500 examples)
