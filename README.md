# HRNet Forward Pass without MMCV

This repository contains a Jupyter notebook demonstrating human pose estimation using the High-Resolution Network (HRNet) model. This document serves as a detailed guide to the code, explaining each step from environment setup to final visualization.
## Introduction
The objective of this notebook is to provide a transparent, step-by-step implementation of human pose estimation. It is designed to show the entire pipeline, from raw image input to a visualized skeleton, without using "black-box" helper functions from external scripts. The HRNet model is a state-of-the-art neural network known for its ability to maintain high-resolution feature representations throughout the entire process, leading to highly accurate keypoint predictions.
## Initial Setup
- Git Clone HRNet Repository
- Install Dependencies
- Add to Python Path
## Model Loading
- Download Pre-trained Weights
- Instantiate and Load Model
## Helper Functions
- Image Preprocessing Function
- Output Decoding and Post-processing Functions
- Pose Visualization Function
## Inference Workflow
- Download and Preprocess Sample Image
- Forward Pass
- Decode Output and Visualize
