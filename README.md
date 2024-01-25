# Project Title :
Machine Learning-Fashion-MNIST-Image-Classification-with-Convolutional Neural Network(CNN)-Project.

## Project Overview :
This project involves building a Convolutional Neural Network (CNN) for image classification using the Fashion-MNIST dataset.
The dataset consists of 60,000 training and 10,000 test examples, each being a 28x28 grayscale image associated with a label from 10 classes. 
The goal is to replace the original MNIST dataset and benchmark machine learning algorithms.

## Project Highlights :
  - **Scaling:** Preprocess the data by scaling with mean and standard deviation.
- **CNN Model:**
  - Three CNN layers:
    1. 2D Convolution with RELU activation, kernel size 2x2, and 32 filters.
    2. 2D Convolution with RELU activation, kernel size 3x3, and 32 filters, followed by MaxPooling and dropout.
    3. 2D Convolution with RELU activation, kernel size 3x3, and 32 filters, followed by MaxPooling and dropout.
  - Final layers: Flatten, Dense with 128 nodes, and 10-node softmax layer.
- **Compilation:**
  - Optimizer: SGD with a learning rate of 0.02, decay of learning rate/10, and momentum of 0.91.
  - Loss: Sparse categorical cross-entropy.
  - Metrics: Accuracy.
- **ModelCheckpoint:**  Saving the model for the best weights.
- **Training:** Training the model for 10 epochs.
- **Data Splitting:** Splitting the data into training and validation sets.
- **Predictions:**
  - Make predictions using the trained model.
  - Showing predictions for test images and comparing them with the test labels.
  - Visualizing predictions through a bar chart.
- **Evaluation:**
  - Plotting test images with correctly and incorrectly highlighted predictions.
  - Predicting the class for a specific test image and comparing it with the test label.
- **Confusion Matrix:** Plotting a confusion matrix and classification report.
  
## Project Preview :
<img src="Images/Do not reject H0.png">
