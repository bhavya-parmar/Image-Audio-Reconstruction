# Image and Audio Reconstruction using Linear Regression and Random Fourier Features (RFF)

This repository contains a mini-project exploring the use of **Random Fourier Features (RFF)** and **Linear Regression** to reconstruct signals from sparse or complete coordinate-based input representations.

## Project Overview

This project is divided into two parts:

### 1. Image Reconstruction

We learn a mapping from pixel coordinates **(X, Y)** to RGB color values **(R, G, B)** using RFF and Linear Regression.

- Input: A standard RGB image.
- Task: Predict the RGB value at each pixel coordinate using RFF-based approximation.
- Output: A reconstructed image.
- Metrics:
  - **Root Mean Squared Error (RMSE)**
  - **Peak Signal-to-Noise Ratio (PSNR)**

### 2. Audio Reconstruction

We learn a mapping from time **t** to amplitude **A** using RFF and Linear Regression.

- Input: A 5-second audio sample.
- Task: Predict audio amplitude over time using RFF-based regression.
- Output: A reconstructed audio waveform.
- Metrics:
  - **Root Mean Squared Error (RMSE)**
  - **Signal-to-Noise Ratio (SNR)**

## Techniques Used

- **Random Fourier Features (RFF)** to approximate the Gaussian kernel.
- **Linear Regression** in transformed feature space.

## References

- [siren.ipynb by Prof. Nipun Batra](https://github.com/nipunbatra/ml-teaching/blob/master/notebooks/siren.ipynb)
- [Audio Reconstruction by Guntas S. Saran](https://github.com/guntas-13/ml-teaching/blob/master/notebooks/audio-reconstruction.ipynb)
