## Lab 6: Hyperparameter Tuning in Neural Networks

## Objective
- Experiment with different hyperparameters to study their impact on neural network performance.
  
### Key Concepts
- MNIST dataset preprocessing
- Hyperparameters: hidden units, learning rate, batch size
- Model training and validation accuracy curves
- Test accuracy comparison

### Implementation
- Built an MLP with configurable hidden units and learning rate.
- Trained models with four different hyperparameter settings.
- Plotted validation accuracy across epochs for each configuration.
- Compared final test accuracies in a summary table.

### Results / Observations
- Best performance was achieved with 256 hidden units, lr=0.001, batch=128 (97.63%).
- Higher learning rate (0.01) reduced accuracy due to unstable convergence.
- Smaller batch sizes led to slightly slower but stable training.
- Visualization helped in understanding trade-offs across configurations.
