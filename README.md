# hyperparameter-tuning-mnist-cnn

This repository contains a hyperparameter tuning experiment for a Convolutional Neural Network (CNN) trained on the MNIST dataset.

Following an initial grid search (1 epoch per configuration), the top 5 parameter sets were selected based on validation accuracy. Each of these is now trained for 100 epochs to benchmark long-term performance and stability.

This is my first machine learning project, and I found it interesting to explore how tuning parameters can significantly impact model performance. Due to limited compute resources, I ran only 1 epoch for each of the 128 different parameter combinations, and then selected the top 5 for full training.