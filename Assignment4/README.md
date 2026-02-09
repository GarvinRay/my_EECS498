# Assignment 4: Object Detection

This assignment is part of EECS 498-007 / 598-005: Deep Learning for Computer Vision (Winter 2022).

## Overview

In this assignment, you will implement object detection models to detect and localize objects in images.

## Notebooks

### One-Stage Detector
- **File**: `one_stage_detector.ipynb`
- **Description**: Implement a fully-convolutional single-stage object detector similar to YOLO (Redmon et al, CVPR 2016). You will train and evaluate your detector on the PASCAL VOC 2007 object detection dataset.

### Two-Stage Detector  
- **File**: `two_stage_detector.ipynb`
- **Description**: Implement a two-stage object detector similar to Faster R-CNN (Ren et al, NeurIPS 2015). This combines a fully-convolutional Region Proposal Network (RPN) and a second-stage recognition network.

## Python Files

- `one_stage_detector.py` - Implementation code for one-stage detector
- `two_stage_detector.py` - Implementation code for two-stage detector
- `a4_helper.py` - Helper functions for this assignment
- `common.py` - Common utilities
- `eecs598/` - Module with data loaders, solvers, and utilities

## Getting Started

1. Open the notebook files in Jupyter or Google Colab
2. Follow the instructions in each notebook
3. Implement the required functions in the `.py` files
4. Train and evaluate your models

## Reference

This assignment is from the Winter 2022 offering of EECS 498-007 / 598-005 at the University of Michigan.
