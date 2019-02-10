# Bike-Sharing-Prediction-Neural-Networks

Developed as a course project in Udacity's **Deep Learning Nanodegree** Program.

The objective of this project is to build a Neural Network from scratch to predict bike rentals daily on an hourly basis.

## Project Details:

* Built a neural network from scratch using Numpy
* Implement sigmoid activation function.
* Implement Forward pass in a Neural Network.
* Calculate the Mean Squared Error and Gradients of Error to propagate backwards.
* Implement Backward pass to update the weights of the Network (Gradient Descent).
* Try different - number of hidden layers, learning rates and training iterations.

## Setup:

To run this project follow these steps:

* Make sure you have Anaconda or Miniconda Package manager installed.
* Clone this repository: `git clone https://github.com/anubhavshrimal/Bike-Sharing-Prediction-Neural-Networks.git`
* `cd Bike-Sharing-Prediction-Neural-Networks`
* `conda env create -f environment.yaml`
* `source activate bike-sharing-prediction`
* `jupyter notebook`
* Open: `Your_first_neural_network.ipynb`

## Performance:

Following are the Training and Validation losses and the predictions made by the Neural Network:

![Train-Val-Loss](plots/Train-Val-Loss.png)
![Actual-vs-Prediction](plots/Actual-vs-Prediction.png)

## Analysis:

Different learning rates, Number of Iterations and Number of Hidden Nodes were tried to see the effects of these hyper parameters. Following are the analysis produced:

![Changing-Iterations](plots/Changing-Iterations.png)
![Changing-Learning-Rate](plots/Changing-Learning-Rate.png)
![Changing-Number-of-Hidden-Nodes](plots/Changing-Number-of-Hidden-Nodes.png)
![Validation-Loss-Change-on-different-Hyper-Parameters](plots/Validation-Loss-Change-on-different-Hyper-Parameters.png)
