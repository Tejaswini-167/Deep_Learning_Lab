## Lab 3: Activation Functions and Their Effects in MLP Performance

### Objective
Analyze the impact of different activation functions on the performance of a Multi-Layer Perceptron (MLP).

### Key Concepts
- Role of activation functions in introducing non-linearity
- Sigmoid, Tanh, ReLU, and Leaky ReLU functions
- Effect on convergence, gradient flow, and overall accuracy

### Implementation
- Implemented MLP models using different activation functions.
- Trained each model on the MNIST dataset.
- Compared training and validation accuracy across activations.
- Visualized loss and accuracy curves for each activation function.

### Results / Observations
- ReLU provided faster convergence and better accuracy compared to Sigmoid and Tanh.
- Sigmoid suffered from the vanishing gradient problem in deeper networks.
- Tanh performed better than Sigmoid but was still slower than ReLU.
- Leaky ReLU reduced the “dying ReLU” problem and improved stability.
