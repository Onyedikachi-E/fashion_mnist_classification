# Module 6 Assignment: Fashion MNIST Classification

This is project is about creating a Convolutional Neural Network (CNN) at Microsoft Ai for image classification on the popular Fashion MNIST datasets from keras library. The datasets is made of about 60,000 28 x 28 grayscale images of 10 fashion category along with a test data of 10,000 images. The model will be trained using dataset from the Fashion MNIST datasets. After the training, the model will be evaluated using random test images from the test data to make classification and compare predicted label and true labels.

The classes are:

Label 	Description
- 0  -	T-shirt/top
- 1  -	Trouser
- 2  -	Pullover
- 3  -	Dress
- 4  -	Coat
- 5  -	Sandal
- 6  -	Shirt
- 7  -	Sneaker
- 8  -	Bag
- 9  -	Ankle boot


## Key Features

- **Fashion MNIST Dataset**: The program is able to load the Fashion MNIST datasets from the keras.datasets. This datasets will be unpacked into test data and train data
- **Data Exploration**: The program will explore tha Fashion MNIST datasests to understand the shape and features of the datasets.
- **Data Transformation**: The program will make some data formatting to change the datatype and normalize the datasets using One Hot Encoding to categorical data.
- **Data Model Creation**: The program will create a model based on Convolutional Neural Network (CNN) using the Sequential()
- **Data Model Visualization**: The program will create visualizations of the model during training based on the metrics = ['accuracy','Precision','Recall']
- **Data Model Testing and Evaluation**: The program will now carry out a test on two random images and make classification and comparison on the test data and 
- **Error Handling**: Added Error Handling to track any exception and print the error as a string or character.
- **Lanuguage Stack**: The entire program was written using Python programming langguage and Jupyter Notebook.

## GitHub Repository
1. 


## Packages Used in the project
- **For Python**
1. Keras - This library is a high level deep learning API. It is ised for building and training neural networks.
2. Matplotlib - This is an extensive python library that is very rich in data visualization and will be used for metric plotting.
3. Numpy - This a python library that used to create and manipulate arrays of any dimension


## How To Use The Program
- **For Python**
1. Load the neccessary packages that will be used in the program
2. Run the cell blocks step by step to perform the different sets of operation
