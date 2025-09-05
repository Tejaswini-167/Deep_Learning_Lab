## Lab 7: Regularization in Neural Networks

### Objective
Study the effect of different regularization techniques (L1, L2, Dropout) on neural network performance.

### Key Concepts
- Overfitting vs. regularization
- L1 and L2 penalties on weights
- Dropout as a form of stochastic regularization
- Comparing validation accuracy and loss across methods

### Implementation
- Built MLP models with configurable regularization (L1, L2, Dropout).
- Trained models on MNIST with 5 different configurations.
- Plotted validation accuracy and loss curves.
- Compared final test accuracies for each technique.

### Results / Observations
- No regularization achieved ~97.4% accuracy, but risk of overfitting.
- L1 regularization led to lower accuracy (~94%) due to stronger weight penalty.
- L2 regularization improved generalization (~96.7%).
- Dropout (0.3) helped prevent overfitting, reaching ~97.1% accuracy.
- L1 + Dropout gave stable performance (~97.0%), showing balanced trade-off.
