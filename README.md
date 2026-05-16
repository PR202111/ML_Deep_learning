# 🧠 ML Deep Learning

A comprehensive collection of educational Jupyter notebooks exploring fundamental concepts of deep learning, neural networks, and optimization techniques from scratch.

## 📚 Overview

This repository contains hands-on implementations and demonstrations of core deep learning concepts including neurons, layers, backpropagation, regularization, and various optimization algorithms. Perfect for students and practitioners looking to understand how neural networks work under the hood.

## 📓 Notebooks

### 1. **BackProp_Neuron.ipynb**
Deep dive into the backpropagation algorithm using a single neuron.
- ReLU activation function and its derivative
- Forward pass computation
- Gradient calculation via chain rule
- Weight and bias updates using backpropagation
- **Key Concepts**: Backpropagation, Gradient descent, Chain rule

### 2. **Dense_layer_class.ipynb**
Implementation of a fully connected (Dense) layer as a Python class.
- Dense layer architecture with multiple inputs and neurons
- Forward propagation through multiple layers
- ReLU activation implementation as a separate class
- Stacking multiple dense layers
- **Key Concepts**: Neural network layers, Matrix operations, Activation functions

### 3. **each_function_NN.ipynb**
Comprehensive exploration of individual neural network components.
- Breaking down neural network operations into modular functions
- Understanding each component's role in the network
- **Key Concepts**: Modularity, Function composition

### 4. **L1_L2_Regularization.ipynb**
Study of regularization techniques to prevent overfitting.
- L1 (Lasso) regularization
- L2 (Ridge) regularization
- Impact on model training and generalization
- **Key Concepts**: Overfitting prevention, Weight penalties, Model complexity control

### 5. **Neurons_layers.ipynb**
Foundation concepts of neurons and network layers.
- Single neuron computations
- Multiple neurons in a layer
- Layer composition and connectivity
- **Key Concepts**: Neurons, Network topology, Forward pass

### 6. **Optimizers.ipynb**
Detailed implementation and comparison of optimization algorithms.
- Momentum-based optimization
- Adaptive learning rate methods
- Softmax activation for multi-class classification
- **Key Concepts**: Optimization algorithms, Convergence, Learning rates

### 7. **spiral_data_classification.ipynb**
End-to-end classification example using the spiral dataset.
- Loading and visualizing the spiral dataset
- Building a neural network classifier
- Training and evaluation
- **Key Concepts**: Classification, Data visualization, Model training

## 🚀 Getting Started

### Prerequisites
- Python 3.7+
- Jupyter Notebook or JupyterLab
- NumPy
- Matplotlib
- NNFS (Neural Networks from Scratch library)

### Installation

```bash
# Clone the repository
git clone https://github.com/PR202111/ML_Deep_learning.git
cd ML_Deep_learning

# Install required packages
pip install numpy matplotlib nnfs
```

### Running the Notebooks

```bash
# Start Jupyter Lab
jupyter lab

# Or start Jupyter Notebook
jupyter notebook
```

Then navigate to the notebook you want to explore and open it.

## 📊 Learning Path

We recommend following these notebooks in order for optimal learning:

1. **Start Here** → `BackProp_Neuron.ipynb` - Understand the basics of backpropagation
2. **Next** → `Neurons_layers.ipynb` - Learn about neurons and layers
3. **Build Skills** → `Dense_layer_class.ipynb` - Implement dense layers
4. **Deepen Understanding** → `each_function_NN.ipynb` - Explore individual components
5. **Advanced Topics** → `Optimizers.ipynb` - Study optimization algorithms
6. **Refinement** → `L1_L2_Regularization.ipynb` - Learn regularization techniques
7. **Practice** → `spiral_data_classification.ipynb` - Apply everything to a real problem

## 🎯 Key Concepts Covered

- **Neural Network Fundamentals**: Neurons, layers, and network architecture
- **Backpropagation**: Forward and backward passes, gradient computation
- **Activation Functions**: ReLU, Softmax
- **Loss Functions**: Mean squared error, Cross-entropy
- **Optimization**: Gradient descent, Momentum, Adaptive methods
- **Regularization**: L1/L2 penalties to prevent overfitting
- **Classification**: Multi-class problems and softmax
- **Practical Implementation**: Building networks from scratch

## 🔧 Technologies & Libraries

- **NumPy**: Numerical computing and linear algebra
- **Matplotlib**: Data visualization
- **NNFS**: Neural Networks from Scratch utilities
- **Jupyter**: Interactive computing environment

## 💡 Learning Outcomes

After exploring these notebooks, you'll be able to:
- Understand how neural networks learn through backpropagation
- Implement neural network layers from scratch
- Apply various optimization algorithms effectively
- Use regularization to improve model generalization
- Build and train classifiers for multi-class problems
- Debug and understand neural network behavior

## 📝 Notes

Each notebook is self-contained but builds upon concepts introduced in earlier notebooks. The code is heavily commented to aid understanding. Don't hesitate to modify and experiment with the code!

## 🤝 Contributing

Feel free to fork this repository, add improvements, or suggest enhancements. This is an educational project meant to help others learn deep learning fundamentals.

## 📖 References

- [Neural Networks from Scratch](https://nnfs.io/)
- [3Blue1Brown Neural Networks](https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi)
- Deep Learning textbooks and academic papers

## 📄 License

This project is open source and available under the MIT License.

---

**Created by**: PR202111  
**Last Updated**: 2026  
**Status**: Active ✨

Happy Learning! 🚀
