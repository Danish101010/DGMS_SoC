# Assignment1: DCGANs for Anime Faces Generation

## Overview

This project explores Deep Convolutional Generative Adversarial Networks (DCGANs) to generate anime faces. The objective is to create realistic anime-style images using a dataset of anime faces.

## Dataset

The dataset comprises anime faces collected from various sources, preprocessed to ensure uniformity and quality. Each image is resized to 64x64 pixels.

## Model Architecture

### Generator Network

The generator transforms random noise into synthetic anime faces. It was experimented with different architectures, varying layers, kernel sizes, strides, and activation functions.

### Discriminator Network

The discriminator distinguishes between real anime faces and generated ones. Various configurations including convolutional layers, dropout, and Leaky ReLU activations were tested.

## Training Process

Training involved iterating through batches of images, updating the generator and discriminator networks. Key hyperparameters: learning rate (0.0002), batch size (64), epochs (100).

## Results and Observations

Experimentation revealed insights:
- **Kernel Size:** Larger sizes captured more global features but increased computational cost.
- **Strides and Filters:** Adjustments affected spatial dimensions and feature extraction.

## Conclusion

This project highlights the application of DCGANs for anime faces generation. Insights into network design and hyperparameter tuning underscore their role in creative AI applications.

