# Rotation-Based Self-Supervised Learning on MNIST

## Overview

This project demonstrates the application of rotation-based self-supervised learning on the MNIST dataset. The goal is to leverage a rotation prediction task to learn invariant representations and improve the model's performance on digit classification tasks.

## Features

- **Rotation Task:**
  - Train the model to predict the rotation angle of MNIST digits.
  - Encourage the model to learn features invariant to rotation.

- **Data Augmentation:**
  - Use data augmentation techniques to generate rotated versions of the training data.

- **Fine-Tuning:**
  - Fine-tune the model on a small labeled dataset for digit classification.
