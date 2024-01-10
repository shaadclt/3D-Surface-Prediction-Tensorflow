# 3D Surface Prediction using TensorFlow

This project demonstrates the creation of a 3D surface prediction model using TensorFlow. The model is trained on a randomly generated dataset and visualizes the predicted surface in a 3D space.

## Getting Started

### Prerequisites
- [TensorFlow](https://www.tensorflow.org/install)
- [NumPy](https://numpy.org/install/)
- [Matplotlib](https://matplotlib.org/stable/users/installing.html)

### Installation
```bash
pip install tensorflow numpy matplotlib
```


## Usage
1. Open the Jupyter Notebook file **ANN_Regression.ipynb**.
2. Run the notebook cell by cell to execute the code.
3. Visualize the generated dataset and the predicted 3D surface.


## Dataset Generation
The dataset is generated with 1000 data points, uniformly distributed between (-3, +3). The target variable Y is calculated as the cosine of (2X[:,0]) plus the cosine of (3X[:,1]).


## Model Architecture
The neural network model consists of:

- Input layer: Dense layer with 128 neurons and ReLU activation.
- Output layer: Dense layer with 1 neuron.


## Model Training
The model is trained using Mean Squared Error (MSE) loss and the Adam optimizer.


## Visualization
Visualize the loss during training and plot the predicted 3D surface.

