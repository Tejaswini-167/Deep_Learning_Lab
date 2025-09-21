# Lab 2: Feedforward Neural Network

### Objective
Implement a forward neural network (MLP) to classify handwritten digits from the MNIST dataset.

### Key Concepts
- Data loading and preprocessing (normalization, reshaping)
- Multi-layer perceptron (dense layers, activation functions)
- Model compilation (loss, optimizer, metrics)
- Training and evaluation on MNIST dataset
- Visualizing predictions and misclassifications

### Implementation
- Loaded and normalized MNIST dataset (pixel values scaled to [0,1]).
- Defined an MLP with input, hidden, and output layers.
- Compiled the model with appropriate optimizer and loss function.
- Trained the model on training data and evaluated on test data.
- Plotted accuracy/loss curves for training vs. validation.
- Displayed sample digits with predicted and true labels.

### Results / Observations
- Achieved high test accuracy (>90%) on MNIST classification.
- Model successfully predicted most digits correctly.
- Some errors occurred on visually ambiguous digits.
- Training curves showed stable convergence.
