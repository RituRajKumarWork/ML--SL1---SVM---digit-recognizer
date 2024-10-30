# SVM Image Classification Project

This project demonstrates an **end-to-end process** for using **Support Vector Machines (SVMs)** to classify images. It leverages **MNIST or Fashion MNIST** datasets to train SVM models with different kernels. We also perform **hyperparameter tuning** with GridSearchCV and explore **dimensionality reduction** using PCA.

---

## Table of Contents
1. [Project Overview](#project-overview)  
2. [Features](#features)  
3. [Installation](#installation)  
4. [Usage](#usage)  
5. [Modeling Process](#modeling-process)  
6. [Results and Observations](#results-and-observations)  
7. [Dependencies](#dependencies)  
8. [License](#license)  

---

## Project Overview

The main objective is to classify images using **pixel data** with **SVMs** and evaluate performance using metrics like **accuracy score** and **confusion matrix**. Several **SVM kernels** (linear, RBF, polynomial) are tested, and **hyperparameters** are optimized to boost accuracy.

---

## Features
- **Data loading and visualization**: Verify images and their labels.
- **Preprocessing**: Normalize pixel values for better training efficiency.
- **Train with multiple kernels**: Explore linear, RBF, and polynomial kernels.
- **Hyperparameter tuning**: Use **GridSearchCV** to find the best parameters.
- **Performance evaluation**: Generate confusion matrices and classification reports.
- **Dimensionality reduction**: Use **PCA** to reduce feature dimensions.

---

## Installation

Clone this repository and install the required libraries:

```bash
git clone <repository-link>
cd <repository-folder>
pip install -r requirements.txt
