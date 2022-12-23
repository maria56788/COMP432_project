# COMP432 Project

### Overview
This project uses convolutional neural networks (CNNs) for classifying images of fruit classes. We trained and tested a CNN model on a dataset of images of fruits, with the goal of accurately identifying the type of fruit in each image. The dataset contains 3326 images which were divided among the 10 classes: apple (319) ,avocado (335) ,banana ( 335) ,cherry (357) ,kiwi (357) ,mango (314) ,pineapple (335) ,strawberries (333)  and watermelon (335). The performance of the model is evaluated using the following metrics: confusion matrix, precision, recall, F1 score and the accuracy. 

### Libraries Used
* torch
* torchvison
* PIL (Python Imaging Library)
* numpy
* os
* matplotlib
* sklearn
* seaborn



### Usage
1. For running  purposes the model is already preloaded and saved using pickle, uncomment [>>> file  = load], to use the pickled model
2. Run and open the Neural Network to Classify Fruits.ipynb file on jupyter notebook.
3. The code assumes all images are stored inside a directory named: 'dataset' which exists in the same directory as the ipynb file itself. 
4. The program will compute and print the confusion matrix, precision, recall, F1 score and the accuracy.