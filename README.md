### Quantum Neural Network and Artificial Neural Network Binary Classification

This repository contains implementations of Quantum Neural Network (QNN) and Artificial Neural Network (ANN) models for binary classification tasks using the MNIST dataset. The QNN implementation utilizes layerwise learning techniques inspired by the work of Oyarce (2021) and is built using the Pennylane-PyTorch library.

#### Features:

- **QNN Implementation**: Quantum Neural Network model leveraging layerwise learning technique.
- **ANN Implementation**: Artificial Neural Network model for comparison purposes.
- **Binary Classification**: Both models are trained and evaluated on binary classification tasks using the MNIST dataset.

#### Usage:

1. Create and activate a virtual environment
```
python3 -m venv venv
```
```
source venv/bin/activate
```
2. Install the libraries
```
pip install pennylane pennylane-sf torch torchvision
```
3. Clone this repository.
4. Follow the instructions to train and evaluate the QNN and ANN models.
5. Experiment with different configurations and parameters to explore the capabilities of quantum and classical neural networks for binary classification tasks.

#### Reference:

For more details on layerwise learning techniques for QNNs, refer to the original work by Felipe Oyarce:

- Oyarce, F. (2021). Layerwise learning for QNNs in Pennylane-PyTorch. [GitHub Repository](https://github.com/felipeoyarce/layerwise-learning/tree/master).

