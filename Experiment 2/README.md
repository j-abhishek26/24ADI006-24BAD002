# Experiment 2: Activation Functions and Optimization Algorithms

**Student:** Abhishek (Roll No: 24BAD002)

## Overview
This experiment compares Sigmoid, Tanh, and ReLU activation functions, and
SGD, Momentum, RMSProp, and Adam optimizers, on an ANN trained on the
scikit-learn `digits` dataset (1,797 samples, 10 classes).

## Results Summary

### Activation Functions (Adam optimizer)
| Activation | Val Accuracy | Val Loss |
|---|---|---|
| sigmoid | 0.9722 | 0.1478 |
| tanh | 0.9806 | 0.0961 |
| relu | 0.9778 | 0.1040 |

### Optimizers (ReLU activation)
| Optimizer | Val Accuracy | Val Loss |
|---|---|---|
| SGD | 0.9611 | 0.1394 |
| Momentum | 0.9833 | 0.0763 |
| RMSProp | 0.9833 | 0.1296 |
| Adam | 0.9750 | 0.1303 |

## Conclusion
ReLU + Adam gave the best combination of convergence speed and final
validation accuracy in this experiment.

