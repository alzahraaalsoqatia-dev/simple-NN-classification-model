# Neural Network Classification using TensorFlow

## Description
This project implements a **Neural Network (Multi-Layer Perceptron - MLP)** using TensorFlow and Keras.  
The model is trained on a synthetic **two-class dataset generated with `make_moons`** from Scikit-learn.

The network learns to classify the two moon-shaped classes and visualizes the decision boundary using Matplotlib.

---

## Technologies Used
- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab / Jupyter Notebook

---

## Features
- Synthetic dataset generation using `make_moons`
- Multi-layer neural network model
- Model training and evaluation
- Accuracy calculation
- Decision boundary visualization
- Data point classification plot

---

## How to Run
Open it directly in **Google Colab** and run all cells.

---

## Input
- Synthetic dataset generated using `make_moons`
- 500 data samples
- Noise level: `0.2`

The dataset contains two classes represented by moon-shaped clusters.

---

## Output
- Trained neural network model
- Classification accuracy
- Decision boundary plot
- Scatter plot of classified points

### Example Output
```text
Accuracy: 0.970
```

---

## Notes
- The dataset is automatically generated within the notebook
- The model uses multiple dense layers with ReLU activation
- Softmax activation is used in the output layer for classification

---

## Future Improvements
- Increase dataset size
- Experiment with different numbers of layers
- Compare activation functions
- Test different optimizers
- Add train/test split for better evaluation
