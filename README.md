# Deep Learning

This repository contains a structured collection of deep learning concepts, implementations, and references.  
The content is organized into three primary directories based on neural network types:

- **ANN** – Artificial Neural Networks  
- **CNN** – Convolutional Neural Networks  
- **RNN** – Recurrent Neural Networks  

The repository provides coverage of foundational and advanced topics commonly used in modern deep learning and neural network–based systems.

---

## 📂 Repository Structure
```
deep-learning/
│
├── ANN/
│ ├── basics
│ ├── optimization
│ ├── regularization
│ └── advanced_topics
│
├── CNN/
│ ├── fundamentals
│ ├── architectures
│ ├── transfer_learning
│ └── generative_models
│
├── RNN/
│ ├── basic_rnn
│ ├── lstm_gru
│ ├── seq2seq_attention
│ └── transformers
│
└── README.md
```


---

## 🧠 Artificial Neural Networks (ANN)

The **ANN** directory contains material related to fully connected neural networks and their optimization.

### Coverage
- Biological inspiration of artificial neurons  
- Historical neural network models (Perceptron, MLP)  
- Network architecture:
  - Input layer  
  - Hidden layers  
  - Output layer  
- Activation functions:
  - Sigmoid  
  - Tanh  
  - ReLU  
  - Leaky ReLU / PReLU  
  - Softmax  
- Forward propagation  
- Loss functions:
  - Mean Squared Error (MSE)  
  - Cross-Entropy Loss  
  - Hinge Loss  
- Backpropagation and gradient computation  
- Gradient descent methods:
  - Batch Gradient Descent  
  - Stochastic Gradient Descent  
  - Mini-batch Gradient Descent  
- Optimization algorithms:
  - Momentum  
  - Nesterov Accelerated Gradient  
  - AdaGrad  
  - RMSProp  
  - Adam  
- Regularization techniques:
  - L1 and L2 regularization  
  - Dropout  
  - Early stopping  
- Hyperparameter configuration:
  - Learning rate  
  - Batch size  
  - Epochs  
  - Network depth and width  
- Vanishing and exploding gradients  
- Weight initialization strategies:
  - Xavier / Glorot  
  - He initialization  
- Batch normalization  

---

## 🖼️ Convolutional Neural Networks (CNN)

The **CNN** directory focuses on neural networks designed for image and spatial data.

### Coverage
- Limitations of fully connected networks for image data  
- CNN advantages:
  - Local connectivity  
  - Parameter sharing  
- Convolution operations:
  - Kernels and filters  
  - Stride and padding  
  - 2D and 3D convolutions  
- Activation functions:
  - ReLU  
  - Leaky ReLU  
  - ELU  
- Pooling layers:
  - Max pooling  
  - Average pooling  
- Fully connected layers and flattening  
- Loss functions for classification and regression  
- CNN architecture design and feature maps  

### Data Processing
- Data normalization  
- Standardization  
- Data augmentation:
  - Rotation  
  - Flipping  
  - Cropping  
  - Noise addition  
  - Color jitter  

### Architectures Covered
- LeNet-5  
- AlexNet  
- VGG-16 / VGG-19  
- Inception (GoogLeNet)  
- ResNet (ResNet-50, ResNet-101)  
- MobileNet    

---

## 🔁 Recurrent Neural Networks (RNN)

The **RNN** directory contains content related to sequence modeling and temporal data.

### Coverage
- RNN architecture and mathematical formulation  
- Forward propagation through time  
- Backpropagation Through Time (BPTT)  
- Training challenges:
  - Vanishing gradients  
  - Exploding gradients  
- Gradient clipping  

### Advanced Architectures
- Long Short-Term Memory (LSTM)  
- Gated Recurrent Units (GRU)  
- Deep RNNs  
- Bidirectional RNNs  

### Applications
- Language modeling  
- Sentiment analysis  
- POS tagging  
- Time-series forecasting  

---

## 🔄 Seq2Seq, Attention & Transformers

Sequence-to-sequence models and transformer architectures are included within the **RNN** directory.

### Coverage
- Encoder–Decoder architectures  
- Handling variable-length sequences  
- Padding and masking  
- Teacher forcing  
- Attention mechanisms:
  - Bahdanau (Additive) Attention  
  - Luong (Multiplicative) Attention  
- Transformer architecture:
  - Self-attention  
  - Positional encoding  
  - Multi-head attention  
  - Feedforward networks  
  - Residual connections  
  - Layer normalization  

### Transformer Models
- BERT  
- GPT  
- RoBERTa  
- ALBERT  
- T5  

### Training and Optimization
- Pre-training objectives (MLM, CLM)  
- Fine-tuning strategies  
- Model compression techniques  
- Libraries and tools:
  - Hugging Face Transformers  
  - DeepSpeed  
  - Mixed precision training  

---

## 🎯 Use Cases and Applications

- Text classification  
- Question answering  
- Machine translation  
- Text summarization  
- Conversational agents  
- Named Entity Recognition (NER)  

---

## 🤝 Contributions

Contributions, improvements, and extensions are welcome via pull requests or issues.

---
