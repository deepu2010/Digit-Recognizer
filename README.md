# Digit-Recognizer
Digit Recognizer project is a part of Kaggle Competition - Digit Recognizer

[Link: https://www.kaggle.com/c/digit-recognizer]

I have figured out the digit recognition problem using Neural Networks and my model is 96.7% accurate.

# Description

MNIST ("Modified National Institute of Standards and Technology") is the de facto “hello world” dataset of computer vision. Since its release in 1999, this classic dataset of handwritten images has served as the basis for benchmarking classification algorithms. As new machine learning techniques emerge, MNIST remains a reliable resource for researchers and learners alike.


# About Dataset:

The data files train.csv and test.csv contain gray-scale images of hand-drawn digits, from zero through nine.

Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255, inclusive.

The training data set, (train.csv), has 785 columns. The first column, called "label", is the digit that was drawn by the user. The rest of the columns contain the pixel-values of the associated image.

Each pixel column in the training set has a name like pixelx, where x is an integer between 0 and 783, inclusive. To locate this pixel on the image, suppose that we have decomposed x as x = i * 28 + j, where i and j are integers between 0 and 27, inclusive. Then pixelx is located on row i and column j of a 28 x 28 matrix, (indexing by zero).

![Digit Recognizer](http://corochann.com/wp-content/uploads/2017/02/mnist_plot-800x600.png)

 # Goal
The goal in this competition is to take an image of a handwritten single digit, and determine what that digit is.
For every ImageId in the test set, you should predict the correct label.
Metric
This competition is evaluated on the categorization accuracy of your predictions (the percentage of images you get correct).

# Skills Used:
1. Python3
2. Data Analysis with Numpy, Pandas
3. Data Visualization with Seaborn and Pandas
4. Sci-Kit Learn library for implementing Machine Learning Algorithms
5. ML algorithms - KNN, Support Vector Machine, Convolutional Neural Networks(CNN)


# My approaches:

After data mining process, I planned to implement Logistic Regression alogrithm which yielded 80% accuracy. However, I re-implemented my model with K-Nearest Neighbors algorithm with Ball Tree Data structure, which gave me 92% accuracy. On my final approach, I implemented Convolutional Neural Networks (CNN) which is now yielding 96.7% accuracy. I'm still planning to improve my model as my target is to achieve 100% accuracy.


