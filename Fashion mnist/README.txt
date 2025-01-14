ReadMe: Fashion MNIST Classification Project

---

Project Overview

This project focuses on classifying images from the Fashion MNIST dataset into 10 fashion categories using a neural network. It includes data preprocessing, model training, evaluation, and visualization.

---

Dataset

Source: Kaggle

Details:

70,000 grayscale images (28x28 pixels)

Classes: T-shirt/top, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle boot

Training Data: 60,000 images

Test Data: 10,000 images

---

Steps to Run

1. Download Dataset: Get it from the link and extract the files.


2. Install Dependencies:

pip install tensorflow pandas numpy matplotlib seaborn idx2numpy


3. Load Data: Use pandas for CSV or idx2numpy for IDX files. Normalize pixel values and one-hot encode labels.


4. Train Model: Build and train a neural network using TensorFlow/Keras.


5. Evaluate & Visualize: Test accuracy, confusion matrix, and sample predictions.