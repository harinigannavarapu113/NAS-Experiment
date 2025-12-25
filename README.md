# NAS-Experiment
Dynamic Neural Architecture Search using PyTorch

**Overview**
This project uses PyTorch to carry out a basic Neural Architecture Search (NAS) experiment.
The objective is to automatically investigate various neural network architectures and find the optimal model without the need for human design.

The experiment evaluates several potential architectures on the MNIST handwritten digit dataset using Random Search and Evolutionary Search techniques.

**Search space**

The neural network architectures are generated dynamically by varying:
Number of hidden layers (2 or 3)
Number of hidden units per layer (32 or 64)
Activation functions (ReLU, Tanh)
This small search space keeps the experiment computationally efficient while clearly demonstrating NAS concepts.

**Methodology**
1.Randomly sample neural network architectures.
2.Build models dynamically using PyTorch.
3.Train each model for a few epochs.
4.Evaluate models using classification accuracy.
5.Estimate computational cost using FLOPs / parameter count.
6.Apply evolutionary search by mutating the best-performing architecture.

**Results**

1.Randomly sample neural network architectures.
2.Build models dynamically using PyTorch.
3.Train each model for a few epochs.
4.Evaluate models using classification accuracy.
5.Estimate computational cost using FLOPs / parameter count.
6.Apply evolutionary search by mutating the best-performing architecture.

**Conclusion**

This project shows how neural network design can be made less labor-intensive by using Neural Architecture Search.
Using straightforward and efficient search techniques, it functions as a beginner-friendly NAS implementation.
