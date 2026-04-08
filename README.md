# Neural Network in NumPy
To demonstrate my understanding of fundamental MLPS, I implemented a fully connected neural network from scratch using only NumPy and matplotlib. Building the model from the ground up helped reinforce my understanding of neural networks beyond high level implementations like PyTorch. The network was evaluated on a set of 10 nonlinear time-series functions derived from a course assignment, and incorporated noise in the training split to simulate aleatoric uncertainty. 

To build this NN, I performed:
- Manual implementation of forward propagation
- Derivation and implementation of backpropagation
- Training using mini-batch gradient descent
- Use of ReLU activations and MSE loss for regression

Contents:
- NeuralNet_with_NumPy.ipynb: full implementation of the neural network and experiments
- NN_test_data.npy: dataset containing the time-series signals

This implementation is intended as an educational, from-scratch exploration of NNs. Some parts of the code (e.g., data handling and splitting) are simplified.


