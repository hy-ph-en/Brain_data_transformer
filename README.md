# Neural Transformer for Brain Data

A collection of Jupyter notebooks implementing and exploring transformer-based neural models on brain and behavioral datasets. The goal of this project is to predict neural activity and behavioral events (e.g., lever pulls) using sequence modeling techniques, apply dimensionality reduction for visualization, and compare different prior configurations and most importantly retain the 3D representation of the data through the process.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Installation](#installation)

---

## Project Overview

This repository provides a suite of tools and example notebooks to:

1. Train transformer-based sequence models on neural recordings (`next_neural_datapoint.ipynb`).
2. Extend modeling to 3D neural representations (`next_neural_datapoint_3d.ipynb`).
3. Incorporate different prior distributions in 3D modeling (`next_neural_datapoint_3d_priors.ipynb`).
4. Predict behavioral events (time to lever pull) from neural data (`predict_time_to_lever_pull.ipynb`).
5. Visualize raw neural anatomy and data structure (`visualize_data_anatomy.ipynb`).
6. Perform PCA and other dimensionality reduction for exploratory analysis (`visualize_data_PCA.ipynb`).

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/neural-transformer-brain-data.git
   cd neural-transformer-brain-data
