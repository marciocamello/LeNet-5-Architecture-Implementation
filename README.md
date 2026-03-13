# Computer Vision Fundamentals with LeNet-5

This project is an implementation of the classic **LeNet-5** architecture using **PyTorch**. It was developed as part of a deep dive into Convolutional Neural Networks (CNNs), exploring how they process and interpret visual data.

## 🚀 Overview

This project is part of the **NLW Operator** event by **Rocketseat** (Python Track). It explores the foundations of computer vision by implementing one of the most influential neural network architectures in history. This project covers the entire pipeline: from data preparation to model training and visualization of learned features.

- **Event**: [NLW Operator](https://www.rocketseat.com.br/nlw)

### Key Topics Covered:
- **CNN Fundamentals**: Understanding how convolutional layers extract spatial features.
- **LeNet-5 Architecture**: Structured implementation of convolutional, pooling, and fully connected layers.
- **Pooling & Padding**: Discussing how to maintain spatial dimensions and the importance of downsampling.
- **MNIST Dataset**: Training and evaluating the model on the handwritten digit dataset.
- **Filter Visualization**: Analyzing the learned weights to understand how the network interprets images.

## 🧠 Model Architecture

The implementation follows a modernized version of the original design by Yann LeCun:
1. **Convolution Layer (C1)**: 6 filters, 5x5 kernel.
2. **Max Pooling (S2)**: 2x2 kernel (modern adaptation for improved performance).
3. **Convolution Layer (C3)**: 16 filters, 5x5 kernel.
4. **Max Pooling (S4)**: 2x2 kernel.
5. **Fully Connected (C5)**: 120 units.
6. **Fully Connected (F6)**: 84 units.
7. **Output Layer**: 10 units (representing digits 0-9).

*Activation Function used: **ReLU***

## 🛠️ Technologies

- **Python 3.12**
- **PyTorch** (with CUDA 12.4 support for GPU acceleration)
- **Torchvision**
- **Matplotlib**
- **UV** (Python package manager)

## 📦 Installation & Setup

This project uses `uv` for fast and reliable dependency management.

```bash
# Clone the repository
git clone https://github.com/marciocamello/LeNet-5-Architecture-Implementation.git
cd LeNet-5-Architecture-Implementation

# Install dependencies and create the virtual environment
uv sync

# Launch the notebook
# Note: Ensure you select the .venv environment as your Jupyter kernel
```

## 📊 Results & Analysis

The implementation includes cells to:
- Visualize MNIST sample images.
- Inspect the initial state of convolutional filters.
- Monitor training performance (loss) across multiple epochs.

---

**Next Steps**: Tomorrow, these core concepts will be applied to implement a **Gesture Detection System**!

---
*Developed by Márcio Camello during the Computer Vision module.*
