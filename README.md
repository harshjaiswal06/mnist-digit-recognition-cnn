# MNIST Digit Recognition using CNN

A handwritten digit classification project built using a Convolutional Neural Network (CNN) with TensorFlow and Keras. The model learns to classify grayscale images of handwritten digits from 0 to 9 using the MNIST dataset.

## Project Overview

This project demonstrates a basic deep learning workflow, including image preprocessing, CNN model development, training, and evaluation.

## Dataset

* **Dataset:** MNIST
* **Training images:** 60,000
* **Test images:** 10,000
* **Image dimensions:** 28 × 28 pixels
* **Image type:** Grayscale
* **Classes:** Digits 0–9

## Model Architecture

The CNN uses the following layers:

1. Convolutional layer with 32 filters
2. Max pooling
3. Convolutional layer with 64 filters
4. Max pooling
5. Flatten layer
6. Fully connected layer with 128 neurons and ReLU activation
7. Output layer with 10 neurons and softmax activation

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Jupyter Notebook / Google Colab

## Getting Started

1. Clone this repository.
2. Install the required libraries.
3. Open `Cnn_Model.ipynb` in Jupyter Notebook or Google Colab.
4. Run the notebook cells in order.

Install the main dependencies:

```
pip install tensorflow numpy matplotlib
```

## Results

The notebook records approximately 99% accuracy in its reported evaluation. See the notebook for the training output and evaluation details.

## Future Improvements

* Separate validation data from the test set
* Visualize training and validation accuracy and loss
* Generate a confusion matrix
* Display sample predictions and confidence scores
* Analyze misclassified digits

## Author

Harsh Jaiswal

GitHub: [harshjaiswal06](https://github.com/harshjaiswal06)
