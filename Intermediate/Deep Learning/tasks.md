# Deep Learning Tasks - Intermediate Level

Complete **ANY TWO** of the following tasks.

---

## Task 1: Convolutional Neural Network Implementation

### Objective
Build and train a CNN for image classification.

### Requirements
1. Implement a CNN architecture with:
   - Multiple convolutional layers
   - Pooling layers
   - Fully connected layers
   - Appropriate activation functions
2. Train on a standard dataset (MNIST, CIFAR-10, or similar)
3. Implement data augmentation
4. Track training/validation metrics
5. Visualize learned filters and feature maps
6. Achieve competitive accuracy (>85% for MNIST, >60% for CIFAR-10)
7. Analyze model performance and errors

### Hints
- Start with a simple architecture and gradually increase complexity
- Use batch normalization for better training
- Monitor for overfitting
- Experiment with different hyperparameters

---

## Task 2: Optimization and Regularization Study

### Objective
Compare different optimization algorithms and regularization techniques.

### Requirements
1. Implement a neural network (CNN or MLP)
2. Compare at least 3 optimization algorithms:
   - SGD with momentum
   - Adam
   - RMSprop
3. Implement and compare regularization techniques:
   - L2 regularization
   - Dropout
   - Early stopping
4. Train multiple models with different configurations
5. Plot and compare:
   - Training curves
   - Validation accuracy
   - Convergence speed
6. Document findings and best practices

### Hints
- Use same architecture for fair comparison
- Log all metrics during training
- Use appropriate learning rates for each optimizer
- Test different dropout rates

---

## Task 3: Transfer Learning Application

### Objective
Apply transfer learning to solve a custom image classification task.

### Requirements
1. Choose a pre-trained model (ResNet, VGG, MobileNet, etc.)
2. Adapt for a specific task:
   - Load pre-trained weights
   - Modify final layers
   - Fine-tune on custom dataset
3. Compare two approaches:
   - Feature extraction (frozen backbone)
   - Fine-tuning (unfrozen layers)
4. Implement proper data preprocessing
5. Evaluate and compare results
6. Analyze what the model learned
7. Document the transfer learning process

### Hints
- Start with smaller learning rates for fine-tuning
- Freeze early layers initially
- Use appropriate data augmentation
- Compare with training from scratch if time permits

---

## Evaluation Criteria

- **Correctness**: Models train successfully and produce results
- **Code Quality**: Well-structured, documented code
- **Performance**: Competitive accuracy for the task
- **Analysis**: Thorough comparison and insights
- **Innovation**: Creative approaches and experiments
