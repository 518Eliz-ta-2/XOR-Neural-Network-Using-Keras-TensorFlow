## XOR-Neural-Network-Using-Keras-TensorFlow
This project implements a simple feedforward neural network to learn the XOR logic function — a classic example that cannot be solved by a single-layer perceptron and requires a hidden layer for non-linear separation.

The XOR (exclusive OR) is a simple logic gate problem that cannot be solved using a single-layer perceptron (a basic neural network model). We can solve this using neural networks. Neural networks are powerful tools in machine learning.

The XOR operation is a binary operation that takes two binary inputs and produces a binary output. The output of the operation is 1 only when the inputs are different.
The main problem is that a single-layer perceptron cannot solve this problem because the data is not linearly separable i.e. we cannot draw a straight line to separate the output classes (0s and 1s)

The neural network learns to solve the XOR problem by adjusting the weights during training. This is done using backpropagation, where the network calculates the error in its output and adjusts its internal weights to minimize this error over time. This process continues until the network can correctly predict the XOR output for all given input combinations.


<img width="850" height="675" alt="Multi-Layer-Perceptron-MLP-diagram-with-four-hidden-layers-and-a-collection-of-single" src="https://github.com/user-attachments/assets/78a56889-2c76-4d62-ad95-09c36d885c48" />


![xor-gates](https://github.com/user-attachments/assets/ef51ae50-ef7f-4bc5-9ed5-b6f803ba00a3)

<img width="850" height="728" alt="Solving-XOR-problem-using-3-conventional-neurons-as-a-2-2-1-MLP-network" src="https://github.com/user-attachments/assets/a7988816-ffff-4186-b620-f2951b504fb6" />
