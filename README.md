Neural Network Implementation from Scratch

Practice Lab Assignment — Generative AI Lab, CSE AIML, MIT Academy of Engineering, Pune.

Objective

Implement a simple feedforward neural network from scratch in Python, without using any in-built deep learning libraries (no TensorFlow, PyTorch, or Keras). The implementation covers forward propagation, backpropagation, loss calculation, gradient descent, model training, and performance evaluation.

Dataset

Iris dataset — 150 samples of iris flowers, 4 numeric features (sepal length, sepal width, petal length, petal width), 3 target classes (Setosa, Versicolor, Virginica). Loaded directly from the URL inside the notebook, so no separate data file is needed.

Task

Multi-class classification — predict the iris species from the four input features.

Model Architecture
Input layer: 4 neurons
Hidden layer: 8 neurons (ReLU activation)
Output layer: 3 neurons (Softmax activation)
Loss function: Cross-Entropy
Optimizer: Batch Gradient Descent
Approach
Load and inspect the Iris dataset.
Split into train/test sets (80/20) before any preprocessing, to avoid data leakage.
Normalize features using training-set statistics only.
One-hot encode class labels.
Initialize weights and biases.
Train for 1000 epochs using manually implemented forward pass, backpropagation, and gradient descent.
Track training and test loss per epoch.
Evaluate on the held-out test set and report accuracy.
Results
Final test accuracy: 100% (may vary slightly by random seed/run).
Training and test loss both decrease steadily, indicating the model learns without overfitting.
Files
FirstName_LastName_GenerativeAILabAssignment.ipynb — main notebook with full implementation, explanations, and results.
How to Run
Clone this repository or download the notebook.
Open it in Jupyter Notebook / JupyterLab / Google Colab.
Run all cells sequentially (Kernel → Restart & Run All). The dataset is fetched automatically from the URL, no manual download needed.
Requirements
Python 3.x
numpy
pandas
matplotlib
Author

Nahush Pramod Deshmukh
PRN: 202502110006
Batch: A3

Declaration

This work is my own and has been completed following academic integrity guidelines.
