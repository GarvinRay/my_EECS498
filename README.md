# EECS498 Deep Learning for Vision

Assignments for EECS498/598: Deep Learning for Computer Vision **Winter 2022**.

This course was offered by the University of Michigan to talk really deep about computer vision especially in deep learning. The assignments cover contents including but not limited to CNN architectures, object detection, image captioning, Transformers, GANs, VAE, etc. Students will benefit a lot from this course.

Find course notes and assignments [here](https://web.eecs.umich.edu/~justincj/teaching/eecs498/WI2022/) and be sure to check out video lectures!

If you do not have access to the video, you can also go through CS231n at Stanford, which has huge overlaps with this course.

All the assignments are done with PyTorch.

## Repository Structure (Winter 2022)

### Assignment 1: PyTorch Basics and k-NN
- **PyTorch 101** (`pytorch101.ipynb`) - Walk you through the basics of working with tensors in PyTorch.
- **k-Nearest Neighbor classifier** (`knn.ipynb`) - Walk you through implementing a kNN classifier.

### Assignment 2: Linear Classifiers and Two-Layer Networks
- **Linear Classifiers** (`linear_classifier.ipynb`) - Walk you through implementing SVM and Softmax classifier.
- **Two-layer Neural Network** (`two_layer_net.ipynb`) - Walk you through implementing a two-layer neural network-based classifier.

### Assignment 3: Fully-Connected and Convolutional Networks
- **Fully-Connected Neural Network** (`fully_connected_networks.ipynb`) - Walk you through implementing Fully-Connected Neural Networks.
- **Convolutional Neural Network** (`convolutional_networks.ipynb`) - Walk you through implementing Convolutional Neural Networks.

### Assignment 4: Object Detection
- **One-Stage Detector** (`one_stage_detector.ipynb`) - Walk you through the implementation of a fully-convolutional single-stage object detector similar to YOLO (Redmon et al, CVPR 2016). You will train and evaluate your detector on the PASCAL VOC 2007 object detection dataset.
- **Two-Stage Detector** (`two_stage_detector.ipynb`) - Walk you through the implementation of a two-stage object detector similar to Faster R-CNN (Ren et al, NeurIPS 2015). This will combine a fully-convolutional Region Proposal Network (RPN) and a second-stage recognition network.

### Assignment 5: RNN/LSTM and Transformers ⭐
- **RNN/LSTM Image Captioning** (`rnn_lstm_captioning.ipynb`) - Walk you through the implementation of vanilla recurrent neural networks (RNN) and Long Short Term Memory (LSTM) RNNs. You will use these networks to train an image captioning model.
- **Transformers** (`Transformers.ipynb`) - Implement the Transformer architecture with multi-head self-attention. You will learn about attention mechanisms and apply Transformers to sequence-to-sequence tasks.

### Assignment 6: Generative Models and Visualization ⭐
- **Generative Adversarial Networks** (`generative_adversarial_networks.ipynb`) - Walk you through the implementation of fully-connected and convolutional generative adversarial networks on the MNIST dataset.
- **Variational Autoencoders (VAE)** (`variational_autoencoders.ipynb`) - Implement Variational Autoencoders, a powerful generative model that learns to encode and decode data while learning a structured latent space.
- **Network Visualization** (`network_visualization.ipynb`) - Walk you through the use of image gradients for generating saliency maps, adversarial examples, and class visualizations.
- **Style Transfer** (`style_transfer.ipynb`) - Learn how to create images with the artistic style of one image and the content of another image.
