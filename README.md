![image](https://github.com/user-attachments/assets/b47574f9-7ad3-4bd3-87eb-4b513915d44c)


# Image Classification Using ANN and CNN on CIFAR-10 Dataset

This project aims to accurately classify images into different categories using artificial neural networks (ANNs) and convolutional neural networks (CNNs). It utilizes the CIFAR-10 dataset, which contains 50,000 training images and 10,000 test images across 10 classes, such as airplanes, cars, cats, and dogs. The goal is to compare the performance of ANN and CNN models for image classification tasks.

# The project involves the following key steps:

Data Exploration: Understanding the dataset structure and visualizing sample images.

Data Preprocessing: Preparing the data for model training by resizing images, normalizing pixel values, etc.

Model Design and Training: Designing and training an ANN for image classification, designing and training a CNN for image classification.

Model Evaluation: Evaluating both models based on accuracy, loss, and other performance metrics.

Comparison of ANN and CNN: Comparing the computational efficiency and classification performance of the two models.

# Performance Comparison

After training both the ANN and CNN models, the following results were obtained:

ANN Performance:
Accuracy: 0.47

Loss: 1.49

CNN Performance:
Accuracy: 0.71

Loss: 0.87

As expected, the CNN outperforms the ANN in terms of both accuracy and loss, as CNNs are specifically designed to handle image data more effectively. However, CNNs are computationally more intensive than ANNs due to their layered architecture.

Learning Rate: Default of 0.001 was found to be the best.

Epochs: The number of epochs was varied to check for overfitting. The ANN model performed best with 6 epochs, while the CNN model performed best with 10 epochs.

# Conclusion

Key Takeaway: CNNs are better suited for image classification tasks due to their specialized architecture, which handles grid-like image data more efficiently.

Computational Efficiency: While CNNs achieve higher accuracy, they are more computationally expensive than ANNs.

Best Model: For the CIFAR-10 image classification task, CNN is the recommended model due to its superior performance in terms of accuracy and loss.

# Python Code

You can view and run the full implementation of this project on Google Colab.

# Requirements

Python 3.x

TensorFlow (for model building and evaluation)

Matplotlib (for visualization)

NumPy (for numerical operations)

To install required dependencies, use the following command:
