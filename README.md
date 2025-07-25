CIFAR-10 Image Classification with TensorFlow

This project implements a Convolutional Neural Network (CNN) using TensorFlow/Keras to classify images from the CIFAR-10 dataset into 10 object categories such as airplane, cat, truck, etc.

Key Features

Built with TensorFlow 2 / Keras

Uses data augmentation

Includes Batch Normalization, Dropout, and EarlyStopping

Model checkpointing for best performance

Achieved Test Accuracy: 84.35%


Dataset

CIFAR-10: 60,000 images (32x32 RGB) in 10 classes

Automatically loaded from keras.datasets.cifar10


Training

Optimizer: Adam

Loss: Sparse Categorical Crossentropy

Epochs: 20 (early stopping may stop sooner)

Batch size: 64

Augmented data using ImageDataGenerator




Output

Plots training and validation accuracy/loss

Saves the best model based on validation accuracy

Prints final test accuracy at the end



---
