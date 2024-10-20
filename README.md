# CNN-for-Fashion-MNIST-and-CIFAR-10
## Introduction
This project focuses on building a Convolutional Neural Network (CNN) to classify images from two datasets: 
- Fashion MNIST
- CIFAR-10
  
The aim is to teach the model to recognize different categories of images, such as clothing items in Fashion MNIST and objects in CIFAR-10. CNNs are particularly effective for image recognition tasks due to their ability to capture spatial hierarchies in images.
## Features
- **Data Handling**:Loaded and explored the Fashion MNIST and CIFAR-10 datasets. Reduced the dataset size for faster training and testing.
- **Preprocessing**:Normalized pixel values to a range of 0-1. Reshaped the images to fit the CNN model structure.
- **CNN Architecture**:Created a CNN with multiple convolutional layers, pooling layers, and dense layers. Used ReLU activation for feature extraction and Softmax activation for classification.
- **Training**:Trained the model on the Fashion MNIST dataset for 25 epochs. Tracked both training and validation accuracy and loss to monitor performance.
- **Evaluation**:Generated predictions on the test data. Evaluated model performance using a confusion matrix and classification report.
## Results
- The model achieved good accuracy on the Fashion MNIST dataset.
- Loss and accuracy graphs showed steady improvement over epochs.
- The confusion matrix and classification report highlighted strong performance in recognizing most clothing categories.
- The setup for CIFAR-10 is in place, with further training needed.
