# Assignment 5: Reducing High-Dimensional Data with PCA

A hands-on exploration of Principal Component Analysis (PCA) for dimensionality reduction using the Human Activity Recognition dataset.

## Overview

This assignment demonstrates how to use PCA to compress high-dimensional sensor data (561 features) from wearable devices into a lower-dimensional space that can be visualized and analyzed more efficiently. You'll compare model performance and training time between the original dataset and PCA-transformed features.

## Dataset

**Human Activity Recognition Using Smartphones**
- **Training set**: 7,352 samples with 561 features
- **Test set**: 2,947 samples with 561 features
- **Activities**: 6 types (Walking, Walking Upstairs, Walking Downstairs, Sitting, Standing, Laying)
- **Features**: Accelerometer and gyroscope sensor readings

## File Structure

```
Assignment-5/
├── README.md                    # This file
├── starter_notebook.ipynb       # Main Jupyter notebook with assignment tasks
└── data/
    ├── train.csv               # Training dataset
    └── test.csv                # Test dataset
```

## Requirements

Install the required Python packages:

```bash
pip install pandas matplotlib seaborn scikit-learn
```

## How to Run

1. Open `starter_notebook.ipynb` in Jupyter Notebook or VS Code
2. Run the cells sequentially from top to bottom
3. Complete the TODO sections marked throughout the notebook
4. Answer reflection questions in the markdown cells

## Assignment Tasks

1. **Load and explore** the high-dimensional dataset
2. **Visualize** data using 2D and 3D PCA
3. **Analyze** explained variance to determine optimal components
4. **Compare** model performance (accuracy, training time) between original and PCA features
5. **Reflect** on when to use dimensionality reduction in production

## Learning Objectives

- Understand the curse of dimensionality
- Apply PCA for dimensionality reduction
- Interpret explained variance and scree plots
- Balance model complexity with performance
- Visualize high-dimensional data in lower dimensions
