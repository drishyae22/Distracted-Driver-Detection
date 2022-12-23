DISTRACTED DRIVER DETECTION


Problem Statement: 
Given the dataset consisting of driver images in the car and corresponding labels for 10 categories (such as safe driving, texting, talking etc.), the task was to build a classification model to predict the category for that image.


Objective:
The training data consisted of 17,943 images, validation data consisted of 4,481 images and testing data consisted of 79,726 images belonging to one of the 10 classes. The task was to predict the category for the testing images.


Goals Achieved:
* I used Image Data Generator to generate the features from the images, resized the images to shape (240,240) and used a certain formatting options on training data such as horizontal flip, shear range, coom range etc to reduce the overfitting.


* I created a CNN model consisting of three Convolution layers along with a Max Pooling layer, followed by a Flatten and 3 Dense layers for classification of images.


* The model gave training accuracy of 97.59% and validation accuracy of 97.52%.