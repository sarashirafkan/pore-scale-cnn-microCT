# pore-scale-cnn-microCT
3D CNN for predicting pore-scale rock properties from micro-CT images
# 3D CNN-Based Digital Rock Analysis

This repository contains the source code used in the study:

"A new insight into digital rock analysis using deep learning: 
A comparative study on the effect of hyperparameter selection and data augmentation"

submitted to *Computers & Geosciences*.

The code implements 3D convolutional neural network (CNN) models for predicting
multiple rock properties from micro-CT images and for evaluating the impact of
hyperparameter configurations and data augmentation strategies.

---

## 📌 Predicted Rock Properties
The models are designed to predict the following properties:
- Porosity (Φ)
- Average pore size (Rp)
- Average throat size (Rth)
- Average pore connection number (Npc)
- Average pore shape factor (Sp)

---

## 🧠 Methodology Overview
- 3D CNN models trained on micro-CT sub-volumes extracted from carbonate rock samples
- Sensitivity analysis of key CNN hyperparameters:
  - Number of convolutional layers
  - Kernel size progression
  - Number of filters
  - Activation functions
  - Learning rate strategies
- Evaluation of computational efficiency alongside predictive accuracy
- Analysis of data augmentation effectiveness across different dataset sizes

---
## 🚀 Usage
The main experiments can be reproduced by running the provided Jupyter notebooks.
All models were developed and tested using Python and standard deep learning libraries.

---
## 📄 License
This project is released under the MIT License.

## 📊 Data Availability
The micro-CT datasets used in this study are available at:
https://doi.org/10.5281/zenodo.18495318
