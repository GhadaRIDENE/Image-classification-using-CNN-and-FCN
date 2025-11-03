# Image-classification-using-CNN-and-FCN

### Project Overview
This project implements **automatic image colorization** — converting grayscale images into color using **Convolutional Neural Networks (CNNs)** and **Fully Convolutional Networks (FCNs)**.  
The aim is to train deep learning models that learn meaningful color mappings from large datasets of natural images.

### Objectives
- Understand and compare **CNN** and **FCN** architectures.
- Build an **encoder-decoder** network for colorization.
- Apply **transfer learning** for feature extraction.
- Evaluate the models visually and quantitatively.

### Background Concepts
Based on *Image Classification, Convolutional Neural Networks, and Transfer Learning*:
- **CNNs** capture hierarchical features (edges → textures → shapes).
- **FCNs** perform **pixel-to-pixel** predictions, ideal for colorization tasks.
- **Autoencoders** and encoder–decoder frameworks are key for reconstructing data.

### Model Architectures

#### 1. CNN-based Model
- **Encoder:** Convolution + ReLU + MaxPooling layers.
- **Decoder:** Upsampling + Convolution to predict color channels.
- **Loss:** Mean Squared Error (MSE) between predicted and true colors.

#### 2. FCN-based Model
- Fully convolutional design, without dense layers.
- Maintains image spatial resolution for pixel-level accuracy.
- Optionally uses skip connections for detail preservation.

### Requirements
Install the dependencies:
pip install requirements.txt