# 🔍 Optimizer Benchmarking on CIFAR-10

## 🧠 Project Overview

This project benchmarks the performance of multiple **machine learning optimizers** on the **CIFAR-10** dataset using a **simple neural network**. The aim is to evaluate how different optimizers influence:

- Accuracy & loss (training and validation)
- Convergence speed
- Training time
- Stability of training

This study isolates the **optimizer’s effect** by keeping the model architecture and hyperparameters constant.

## 🚀 Optimizers Tested

- SGD
- NAG
- RMSprop
- NAdam
- SGDR
- SGD With step Decay


## 🧪 Experiment Setup

- **Dataset**: CIFAR-10 (60k 32x32 RGB images across 10 classes)  
- **Model**: Lightweight NN (to ensure quick, repeatable testing)  
- **Framework**: Tensorflow
- **Epochs**: Fixed (e.g., 50 epochs)  
- **Batch Size**: 64  
- **Metrics**:  
  - Final accuracy  
  - Final loss  
  - Training time    
  - Learning curve trends
  - Confusion Matrix
