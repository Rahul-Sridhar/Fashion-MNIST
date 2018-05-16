### **Description:** Classification on images using Keras Deep Learning framework for Fashion MNIST dataset.


* Step-1: Download dataset from [https://www.kaggle.com/zalando-research/fashionmnist/data](https://www.kaggle.com/zalando-research/fashionmnist/data), store it in dataframe. 
* Step-2: Read the csv file using pandas and convert the dataframe into numpy array and store in X and Y
* Step-3: Create a one_hot_encoding function to convert the format of variable Y into that of the output of the convolutional neural network.
* Step-4: Create the Model Layer(CONV->MAX_POOL->CONV->MAX_POOL->CONV->MAX_POOL->FC300 followed by softmax)
* Step-5: Compile the Model and fit the numpy arrays X and Y.
* Step-6: Plot the Train and Validation loss and accuracy.


# Conclusion

* The  Algorithm gives a training accuracy of 96.33% and validation accuracy of 88.62%. With just a 5 Layer Architecture we are able to achieve good accuracy.

|       Hyperparameters |           Value            |
|:----------------------|:--------------------------:|
|     Loss Function     |  categorical_crossentropy  |
|       Optimizer       |           Adam             |      
|   Validation Split    |           0.33             |
|      Batch Size       |            32              |
