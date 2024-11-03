Simple Neural Network from Scratch
Overview
This project implements a simple feedforward neural network (MLP) from scratch using Python. The network is capable of classifying data generated from the "make_moons" dataset, demonstrating key concepts in neural networks, including forward propagation, backpropagation, and gradient descent.

Project Structure
The project consists of the following main files:

engine.py: Contains the Value class that implements automatic differentiation, enabling gradient calculation for optimization.
nn.py: Defines the Module, Neuron, Layer, and MLP classes, which together make up the neural network architecture.
main.py: The entry point of the project that initializes the model, trains it on the dataset, and visualizes the results.
Requirements
To run this project, you'll need:

Python 3.x
NumPy
Matplotlib
scikit-learn
You can install the required libraries using pip:

bash
Copy code
pip install numpy matplotlib scikit-learn
Usage
Clone the repository:

bash
Copy code
git clone https://github.com/Arakalgudmaheshsurya/is-640-nn.git

Run the main script:

bash
Copy code
python main.py
The script will generate the dataset, train the neural network, and display a plot showing the decision boundary along with the classified data points.

Key Features
Custom Neural Network Implementation: Build a neural network from scratch with fully customizable layers and activation functions.
Automatic Differentiation: The Value class handles the gradients required for backpropagation automatically.
Visualization: The project provides visual feedback on how well the model is classifying the input data.
License
This project is open-source and available under the MIT License.

Acknowledgments
Inspired by various resources on neural networks and machine learning.