# Quantum-Open-Source-Foundation-Mentorship
In this task, the below neural network is trained to approximate a random quantum state. The aim is to investigate the effect of number of layers in the accuracy of the approximation. This notebook contains the following parts:
- Model Design and Implementation
- Stochastic Gradient Descent
- Training the QNNs
- Training QNNs with 1 to 10 layers
- Training QNNs with 1 to 6 layers, averaging over 5 rounds for each QNN to reduce the effect of random initialization
- Discussion about the barren plateau
- Trying different loss function, Kullback–Leibler divergence
- Comparing using of parameter shift rule with numerical method in training process
- Running the training process, for QNNs with 1 to 5 layers, for 3 different random target states and averaging the results to see the effect of random target states
- Implementing a different design for QNNs’ layers, referred in this notebook as type 2 design
- Training type 2 QNNs with 1 to 6 layers
- Training type 2 QNNs with 1 to 6 layers, averaging over 5 rounds for each QNN to reduce the effect of random initialization
- Investigating another scenario with type 1 QNNs’ design, by using Swap test to calculate the overlap between states
