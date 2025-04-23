# hyperparameter-tuning-mnist-cnn

This project is about tuning hyperparameters for a Convolutional Neural Network (CNN) trained on the MNIST dataset.

I started with a grid search, testing 128 different parameter combinations. Each one was trained for just 1 epoch because of limited compute. Then I picked the top 5 setups based on validation accuracy.

These top 5 models are now trained longer, but not for a fixed number of epochs. Training stops if the model doesn't improve for 5 epochs in a row.

This is my first machine learning project, and it’s been interesting to see how much tuning can affect performance.
