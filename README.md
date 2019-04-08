# Multi Layer Neural Network
A multi layer neural network written in Python 3, which can be trained to solve the XOR problem. It demonstrates back
propagation using Sigmoid as the activation function.

It is built from scratch without using a machine learning library. There are no dependencies except the mathematics
library numpy.

# Network Architecture
![alt text](./neural_network_structure.png)

# Training Set
The Output is 1 if either Input 1 or Input 2 are 1, but not both. Input 3 does not have any bearing on the Output.
The challenge is to train a neural network to detect the pattern using this training set.

| Input 1 | Input 2 | Input 3 | Output |
|---------|---------|---------|--------|
| 0       | 0       | 1       | 0      |
| 0       | 1       | 1       | 1      |
| 1       | 0       | 1       | 1      |
| 0       | 1       | 0       | 1      |
| 1       | 0       | 0       | 1      |
| 1       | 1       | 1       | 0      |
| 0       | 0       | 0       | 0      |

# Usage
```
pip install numpy
```
```
python3 main.py
```
