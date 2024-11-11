# Support Vector Boosting Machine (SVBM) - Version 1.0

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/junbolian/SVBM)
![GitHub repo size](https://img.shields.io/github/repo-size/junbolian/SVBM)
![GitHub language count](https://img.shields.io/github/languages/count/junbolian/SVBM)
![GitHub last commit](https://img.shields.io/github/last-commit/junbolian/SVBM)
![GitHub issues](https://img.shields.io/github/issues/junbolian/SVBM)
![GitHub forks](https://img.shields.io/github/forks/junbolian/SVBM)
![GitHub stars](https://img.shields.io/github/stars/junbolian/SVBM)
![GitHub watchers](https://img.shields.io/github/watchers/junbolian/SVBM)
![GitHub contributors](https://img.shields.io/github/contributors/junbolian/SVBM)

## Introduction

Welcome to the **Support Vector Boosting Machine (SVBM)** repository! This repository hosts the source code for the SVBM model—a machine learning framework that synergizes the AdaBoost algorithm and residual connections to elevate the performance of standard Support Vector Machines (SVMs). The provided documentation and examples will guide you through effectively applying SVBM to your projects.

## Overview

The SVBM model is discussed in the paper titled *"Support Vector Boosting Machine (SVBM): Enhancing Classification Performance with AdaBoost and Residual Connections"* by **Junbo Lian**. SVBM incorporates an RBF kernel by default and allows for additional enhancements like the **Linearly Programmed SVM (LPSVM)** for improved sparsity and performance. It can be seamlessly integrated with various optimization algorithms for further performance boosts.

### Key Features
- **Subsampled SVM with RBF Kernel**: Employs an SVM with an RBF kernel to achieve robust and adaptable classification.
- **Linearly Programmed SVM (LPSVM)**: Optional implementation for increased efficiency and reduced model complexity.
- **Optimization Algorithm Integration**: Can be paired with optimization algorithms to fine-tune model performance.
- **Residual Connections**: Improves classification accuracy and mitigates the risk of overfitting.
- **Modular and Flexible Design**: Easily extendable for research or practical application purposes.

### Parameters:
- **`X`**: Input data matrix.
- **`y`**: Labels corresponding to the input data.
- **`kernel`**: Type of kernel function (e.g., `'RBF'`).
- **`parameters`**: Customizable SVM parameters for model tuning.

## Installation

Clone this repository and ensure all dependencies are properly installed:

```bash
git clone https://github.com/junbolian/SVBM.git
cd SVBM
```

## Usage Example

Here's a simple usage example in MATLAB:

```matlab
% Load your dataset into variables X and y
model = SVBM(X, y, 'RBF', parameters);
[accuracy, predictions] = model.trainAndTest();
```

## Citation

If this repository aids your research, please cite the associated paper:

**Junbo Jacob Lian**  
*"Support Vector Boosting Machine (SVBM): Enhancing Classification Performance with AdaBoost and Residual Connections"*  
[DOI: 10.48550/arXiv.2410.06957](https://doi.org/10.48550/arXiv.2410.06957)
