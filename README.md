# Minist Image Classification using CNN

## Overview

This project uses a Convolutional Neural Network (CNN) built with TensorFlow and Keras to classify Minist images. It distinguishes between different digit classes (0-9) and provides accuracy metrics for the classification task.

## Features

* Classify Minist images as various digit classes (0-9)
* Provide accuracy metrics for the classification task
* Utilize a structured dataset split into training and test sets for model training
* Evaluate model performance using accuracy metrics

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Structured dataset containing images of handwritten digits (0-9)

## Dataset

* The dataset consists of 60,000 images of handwritten digits, split into 50,000 training images and 10,000 test images.
* Each image is labeled with the corresponding digit class (0-9).

## Model Architecture

* The CNN model consists of the following layers:
	+ Conv2D (32 filters, kernel size 3x3)
	+ MaxPooling2D (pool size 2x2)
	+ Flatten()
	+ Dense (128 units, activation='relu')
	+ Dropout (0.2)
	+ Dense (10 units, activation='softmax')

## Training

* The model was trained using the Adam optimizer and categorical cross-entropy loss.
* Training was done on the training set for 10 epochs with a batch size of 128.

## Results

* Accuracy on the test set: 98.5%
* Loss on the test set: 0.035

## Acknowledgments

* This project was inspired by the Minist dataset and the CNN architecture.
* Thanks to the authors of the Minist dataset for providing the data.

## Contact

If you have any questions or suggestions, please feel free to contact me at [rahulkannan0784@gmail.com](mailto:rahulkannan0784@gmail.com).
