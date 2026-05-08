# Transformer-Based Cryptanalysis of Bilinear Compressive Security (BCS)

## Overview

This project presents a simulation and exploratory analysis of the **Bilinear Compressive Security (BCS)** framework introduced by Flinth et al. The objective is to study the security properties of BCS under adversarial conditions using modern **deep learning techniques**, specifically transformer-based architectures.

BCS is a signal encryption paradigm that combines **compressed sensing** with **random convolutional filtering**, forming a bilinear structure:

\[
y = h * (Qx)
\]

where:
- **Q** = secret linear transformation (key matrix)
- **h** = randomly generated convolutional filter
- **x** = plaintext signal
- **y** = encrypted observation

This project investigates whether repeated observations of such outputs can leak structural information when analyzed using AI models.

---

## Author

**Name:** Meraol Alemayehu  
**Education:** MSc in Computer Science (Ongoing)  
**Undergraduate:** BSc in Information Technology, Arba Minch University  
**Field of Interest:** Artificial Intelligence & Cybersecurity  
**Email:** meralex3939@gmail.com  

---

## Project Visibility Notice

This project was originally developed in a private repository as part of ongoing research in cybersecurity and machine learning.

It has now been made publicly available strictly for **portfolio and academic preview purposes**, demonstrating applied research in:

- Bilinear Compressive Security (BCS)
- Transformer-based adversarial modeling
- Signal processing and cryptographic inference

The project remains **under active development** and may be extended or improved over time.

---

## Problem Statement

Compressed sensing-based encryption systems are known to be vulnerable under known-plaintext attacks. The BCS model attempts to improve security by introducing a bilinear transformation involving a random convolution filter.

However, it remains unclear whether modern AI systems can extract hidden structure from multiple encrypted observations without access to the key or filter.

This project explores that question.

---

## Objectives

- Simulate a Bilinear Compressive Security (BCS) encryption environment  
- Generate synthetic encrypted signal data using matrix transformations and convolution  
- Develop a transformer-based neural network for adversarial inference  
- Analyze whether AI models can detect hidden statistical structures  
- Evaluate the robustness of BCS under repeated observation attacks  

---

## Methodology

### 1. BCS Signal Simulation
- Randomly generated key matrix \(Q\)
- Sparse or structured input signals \(x\)
- Random convolution filter \(h\)
- Output generation: \(y = h * (Qx)\)

### 2. Adversarial Learning Model
- Transformer encoder-based architecture
- Sequence embedding of encrypted signals
- Attention-based feature extraction
- Classification of latent structure patterns

### 3. Evaluation Strategy
- Accuracy of adversarial inference
- Sensitivity to sparsity level
- Generalization across multiple signal distributions

---

## Model Architecture

- Input Embedding Layer (Linear Projection)
- Positional Encoding
- Multi-head Self-Attention (Transformer Encoder)
- Feedforward Neural Network Head
- Softmax Classification Layer

---

## Technologies Used

- Python
- PyTorch
- NumPy
- Scikit-learn
- Transformer Neural Networks

---

## Key Findings (Experimental)

- Transformer models can learn weak statistical patterns from BCS outputs  
- Full recovery of the secret key \(Q\) is not achieved  
- Structural leakage increases with repeated observations  
- Sparsity of input signals significantly impacts inference success  
- Results support theoretical claims on conditional security of BCS  

---


 
