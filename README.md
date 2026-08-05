# Image Data Processing and Feature Analysis for Agricultural Applications

## Project Overview
This project presents a deep learning framework for agricultural image analysis using Hyperspectral Imaging (HSI). The proposed system processes hyperspectral image cubes through multiple preprocessing stages and classifies plum samples into different storage conditions using a 3D Convolutional Neural Network (3D CNN).

## Features
- Hyperspectral image preprocessing
- Automatic ROI extraction
- Multiplicative Scatter Correction (MSC)
- Savitzky–Golay spectral smoothing
- PCA-based dimensionality reduction
- Patch extraction for deep learning
- 3D CNN-based classification
- Performance evaluation using multiple metrics

## Methodology

### Data Preprocessing
- Load hyperspectral MAT image cubes
- ROI extraction
- MSC preprocessing
- Savitzky–Golay smoothing
- PCA feature extraction
- Patch generation

### Deep Learning Model
- 3D Convolutional Neural Network (3D CNN)
- Batch Normalization
- Max Pooling
- Dropout Regularization
- Dense Classification Layer
- Adam Optimizer

## Dataset

The dataset consists of hyperspectral images of plum samples collected at different storage stages.

Classes:
- PlumBefore
- Plum12hr
- Plum24hr
- Plum48hr

## Technologies Used

- Python
- Google Colab
- TensorFlow / Keras
- NumPy
- SciPy
- Scikit-learn
- OpenCV
- Matplotlib
- Joblib

## Project Workflow

MAT Cube
      │
      ▼
ROI Extraction
      │
      ▼
MSC
      │
      ▼
Savitzky–Golay Smoothing
      │
      ▼
PCA
      │
      ▼
Patch Extraction
      │
      ▼
3D CNN
      │
      ▼
Classification

## Results

The proposed framework performs hyperspectral image preprocessing and feature extraction before classifying plum quality using a 3D CNN. The workflow is designed to improve spectral quality, reduce dimensionality, and enhance classification performance.

## Repository Structure

├── Welcome_To_Colab_fixed.ipynb
├── README.md
└── requirements.txt

## Author
Harsha KP
Meghna Lakshmi M
