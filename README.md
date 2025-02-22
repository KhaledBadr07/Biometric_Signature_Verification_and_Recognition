# Biometric_Signature_Verification_and_Recognition
# Signature Verification and Recognition

## Overview
This repository contains two approaches for biometric signature verification and recognition:

1. **Conventional Method**: A shape-based algorithm that extracts handcrafted features from signatures.
2. **Deep Learning Method**: A CNN-based Siamese network to learn signature similarities for verification.

## Dataset
The dataset consists of real and forged signatures


## Methodology
### 1. Conventional Method
- Extracts features based on shape and texture.
- Extract elastic contours to represent signature shapes.
- Uses classification algorithms (e.g., SVM, k-NN) to differentiate between real and forged signatures.

### 2. Deep Learning (Siamese Network)
- Uses a convolutional neural network (CNN) to learn feature embeddings.
- Compares embeddings using contrastive loss to determine similarity.

## Installation
Clone the repository and install dependencies:
```bash
git clone https://github.com/yourusername/signature-verification.git

```



## Results
- The conventional method provides a baseline with feature-based classification.
- The Siamese CNN model improves accuracy by learning deep representations of signatures.

## Contributors
- Khaled Badr
- Hana Hesham
- Hazem Zakaria


