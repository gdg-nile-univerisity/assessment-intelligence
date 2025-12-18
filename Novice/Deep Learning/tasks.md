# Deep Learning Tasks - Novice Level

Complete **ANY TWO** of the following tasks.

---

## Task 1: Implement a Simple Neural Network

### Objective
Build a basic neural network from scratch using numpy.

### Requirements
1. Implement a single-layer neural network (perceptron)
2. Include the following components:
   - Forward propagation
   - An activation function (sigmoid or ReLU)
   - Loss calculation (MSE or cross-entropy)
3. Test your network on a simple dataset (e.g., AND/OR logic gates)
4. Document your implementation with comments
5. Visualize the decision boundary or predictions

### Hints
- Start with a simple architecture
- Use matrix operations for efficiency
- Test with small, synthetic datasets first

---

## Task 2: Activation Functions Exploration

### Objective
Implement and compare different activation functions.

### Requirements
1. Implement at least 4 activation functions:
   - Sigmoid
   - Tanh
   - ReLU
   - Leaky ReLU
2. Implement their derivatives
3. Create visualizations showing:
   - Function outputs across a range of inputs
   - Derivative values
4. Demonstrate their behavior in a simple network
5. Discuss advantages and disadvantages of each

### Hints
- Use numpy for efficient computation
- Plot functions in the range [-10, 10]
- Consider gradient flow during backpropagation

---

## Task 3: Training a Network with Backpropagation

### Objective
Implement backpropagation to train a simple neural network.

### Requirements
1. Create a 2-layer neural network (input → hidden → output)
2. Implement:
   - Forward propagation
   - Backpropagation algorithm
   - Weight updates using gradient descent
3. Train on a binary classification problem
4. Plot the training loss over epochs
5. Report final accuracy

### Hints
- Start with a small number of neurons
- Use appropriate learning rate
- Monitor loss to verify learning is occurring
- Use a simple synthetic dataset

---

## Evaluation Criteria

- **Correctness**: Implementation produces expected results
- **Code Quality**: Clean, readable, well-commented code
- **Documentation**: Clear explanations of approach and results
- **Understanding**: Demonstrates grasp of fundamental concepts
