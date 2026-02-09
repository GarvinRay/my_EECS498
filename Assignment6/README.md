# Assignment 6: Generative Models and Network Visualization

This assignment is part of EECS 498-007 / 598-005: Deep Learning for Computer Vision (Winter 2022).

## Overview

In this assignment, you will implement and experiment with generative models (GANs and VAEs) and network visualization techniques.

## Notebooks

### Generative Adversarial Networks (GANs)
- **File**: `generative_adversarial_networks.ipynb`
- **Description**: Implement fully-connected and convolutional generative adversarial networks. You will train GANs to generate realistic images from random noise.

### Variational Autoencoders (VAE) ⭐
- **File**: `variational_autoencoders.ipynb`
- **Description**: Implement Variational Autoencoders (VAEs), a powerful generative model that learns to encode and decode data while learning a structured latent space.

### Network Visualization
- **File**: `network_visualization.ipynb`
- **Description**: Learn how to visualize and understand what neural networks have learned. Implement saliency maps, adversarial examples, and class visualizations using image gradients.

### Style Transfer
- **File**: `style_transfer.ipynb`
- **Description**: Implement neural style transfer to create images with the artistic style of one image and the content of another image.

## Python Files

- `gan.py` - Implementation code for GANs
- `vae.py` - Implementation code for VAEs
- `network_visualization.py` - Implementation code for visualization techniques
- `style_transfer.py` - Implementation code for style transfer
- `a6_helper.py` - Helper functions for this assignment
- `eecs598/` - Module with data loaders, solvers, and utilities
- `images/` - Sample images for style transfer

## Key Concepts

- Generative Adversarial Networks (GANs)
- Generator and Discriminator networks
- Variational Autoencoders (VAEs)
- Latent space representation
- Reparameterization trick
- Saliency maps and gradient-based visualization
- Adversarial examples
- Neural style transfer

## Getting Started

1. Open the notebook files in Jupyter or Google Colab
2. Follow the instructions in each notebook
3. Implement the required functions in the `.py` files
4. Experiment with different architectures and hyperparameters

## Reference

This assignment is from the Winter 2022 offering of EECS 498-007 / 598-005 at the University of Michigan.
