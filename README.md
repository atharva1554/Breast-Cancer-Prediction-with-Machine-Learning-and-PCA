# Breast Cancer Prediction with Machine Learning and PCA

## Overview

This repository contains a machine learning project focused on predicting breast cancer outcomes using various machine learning algorithms and Principal Component Analysis (PCA) for dimensionality reduction. The project aims to build a robust model to assist in early detection and diagnosis of breast cancer.

## Table of Contents

- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Data](#data)
- [Models](#models)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Breast cancer detection relies on analyzing patient data to identify whether the cancer is malignant or benign. This project employs various machine learning algorithms and dimensionality reduction techniques like PCA to improve model performance and interpretability.

## Project Structure

```
Breast-Cancer-Prediction-with-Machine-Learning-and-PCA/
│
├── data/               # Dataset files
├── notebooks/          # Jupyter notebooks for analysis and modeling
├── scripts/            # Python scripts for data processing and modeling
├── models/             # Saved model files
├── results/            # Output results such as reports and visualizations
├── images/             # Images used in the project and README
├── README.md           # Project README file
└── requirements.txt    # List of dependencies
```

## Data

The dataset used in this project is the Breast Cancer Wisconsin (Diagnostic) dataset, which includes features such as:

- Mean radius
- Mean texture
- Mean perimeter
- Mean area
- Mean smoothness
- Mean compactness
- Mean concavity
- Mean concave points
- Mean symmetry
- Mean fractal dimension
- Radius error
- Texture error
- Perimeter error
- Area error
- Smoothness error
- Compactness error
- Concavity error
- Concave points error
- Symmetry error
- Fractal dimension error
- Worst radius
- Worst texture
- Worst perimeter
- Worst area
- Worst smoothness
- Worst compactness
- Worst concavity
- Worst concave points
- Worst symmetry
- Worst fractal dimension
- Diagnosis (M = malignant, B = benign)



## Models

The project explores various machine learning models, including:

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

PCA is applied to reduce dimensionality and improve model performance. Each model's performance is evaluated based on accuracy, precision, recall, and F1-score.


## Results

The results of our models, including their performance metrics and visualizations, are documented in the `results/` directory. This includes visualizations such as confusion matrices, ROC curves, and feature importance plots.



## Installation

To set up this project locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/atharva1554/Breast-Cancer-Prediction-with-Machine-Learning-and-PCA.git
   ```

2. Navigate to the project directory:
   ```sh
   cd Breast-Cancer-Prediction-with-Machine-Learning-and-PCA
   ```

3. Create a virtual environment and activate it (optional but recommended):
   ```sh
   python -m venv venv
   source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
   ```

4. Install the required dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage

To start working with this project, you can explore the Jupyter notebooks in the `notebooks/` directory. These notebooks cover data exploration, preprocessing, PCA, model training, and evaluation. The `scripts/` directory also contains Python scripts for specific tasks such as data cleaning and model training.

## Contributing

We welcome contributions to this project. If you have suggestions for improvements, new features, or bug fixes, please open an issue or submit a pull request. For major changes, please discuss them with us first.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
