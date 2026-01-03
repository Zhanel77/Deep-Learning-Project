# Deep Learning Course Project

This repository contains the implementation and experimental study for the **Deep Learning Course Project** at **Astana IT University**.  
The project explores foundational and modern deep learning techniques through a sequence of controlled experiments, progressing from multilayer perceptrons to convolutional neural networks and transfer learning.


## Experiments Overview

The project consists of four main experimental sections:

1. **MLPs and Universal Approximation**
   - Activation function comparison (Sigmoid, Tanh, ReLU)
   - Width vs approximation quality
   - MNIST classification

2. **Optimization and Training Dynamics**
   - Optimizer comparison (SGD, RMSprop, Adam)
   - Learning rate schedules
   - Gradient checking

3. **CNN from Scratch (NumPy)**
   - Manual implementation of convolution, pooling, and backpropagation
   - Filter and feature map visualization
   - Pooling ablation study (max vs average pooling)

4. **Modern Architectures and Transfer Learning**
   - Residual connections and gradient flow
   - ResNet18 from scratch vs pretrained
   - Data augmentation on medical images

---

## Setup Instructions

## Python version <= 3.12.x

### 1. Clone the repository

```bash
git clone https://github.com/Zhanel77/deep-learning-course-project.git
cd deep-learning-course-project
```
### 2. Create a virtual environment (recommended)

Linux / macOS

```bash
python3 -m venv venv
source venv/bin/activate
```

Windows
```bash
python -m venv venv
venv\Scripts\activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### Running Experiments
***just click Run All button in each section***

## Authors

- Koblandy Seipolla
- Zhanel Kuandyk
- Astana IT University
- Deep Learning Course, Fall 2025