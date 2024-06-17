# Sunspot Prediction with Neural Networks

This project uses a neural network model to predict sunspots. The model is built using TensorFlow and the data is processed using NumPy and Matplotlib.

## Overview

The project involves the following steps:

1. **Importing necessary libraries**: The required Python libraries such as TensorFlow, NumPy, Matplotlib, and csv are imported.

2. **Downloading and previewing the dataset**: The sunspot dataset is downloaded and visualized using a utility function `plot_series`.

3. **Splitting the dataset**: The dataset is split into training and validation sets.

4. **Preparing features and labels**: A windowed dataset is prepared using the `windowed_dataset` function.

5. **Building the model**: A Convolutional Neural Network (CNN) model is built using TensorFlow's Keras API. The model architecture includes Conv1D, LSTM, Dense, and Lambda layers.

6. **Tuning the learning rate**: The learning rate is tuned for the model's Stochastic Gradient Descent (SGD) optimizer.

7. **Training the model**: The model is trained on the windowed dataset.

8. **Model prediction**: The trained model is used to predict sunspots in the validation set.

## Usage

To use this project, you need to have Python installed along with the TensorFlow, NumPy, Matplotlib, and csv libraries. You can run the script in a Jupyter notebook or any Python environment.

## Contribution

Contributions to this project are welcome. Please ensure that you update the README.md file with details of your contribution.

## License

This project is open-sourced under the MIT License. See the LICENSE file for more details.
