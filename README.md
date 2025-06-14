# PredictDiamondPrice
A comprehensive machine learning system for predicting diamond prices using supervised learning algorithms. This project implements and compares six different ML models across both regression and classification tasks.

## Overview
The PredictDiamondPrice system analyzes diamond characteristics to predict pricing through multiple machine learning approaches. The project supports both continuous price prediction (regression) and diamond categorization (classification) using a standardized dataset schema.

## Dataset
The system utilizes two primary CSV datasets with comprehensive diamond characteristics:

- **Training Dataset**: diamonds-train.csv - Used for model training and cross-validation
- **Test Dataset**: diamonds-test.csv - Used for independent model evaluation diamonds-test.csv:1-5

## Data Schema
Each dataset contains 11 columns capturing both physical and quality attributes:

Column	Type	Description
id	Integer	Unique diamond identifier
carat	Float	Diamond weight in carats
cut	Categorical	Cut quality (Fair, Good, Very Good, Premium, Ideal)
color	Categorical	Color grade (D, E, F, G, H, I, J)
clarity	Categorical	Clarity grade (IF, VVS1, VVS2, VS1, VS2, SI1, SI2, I1)
depth	Float	Depth percentage
table	Float	Table percentage
x, y, z	Float	Physical dimensions in millimeters
price	Integer	Price in US dollars (target variable)

## Machine Learning Models
The system implements six supervised learning algorithms:

### Regression Models
- **Multiple Linear Regression (MLR)** - Linear relationship modeling
- **k-Nearest Neighbors (k-NN)** - Instance-based learning
- **Multi-Layer Neural Network with Backpropagation (MLNN-BP)** - Deep learning approach

### Classification Models
- **Logistic Regression (LR)** - Linear classification
- **Support Vector Machine (SVM)** - Margin-based classification
- **Multi-Layer Neural Network with Backpropagation (MLNN-BP)** - Neural network classification

## Key Features
- **Dual-Task Support**: Both regression (price prediction) and classification (categorization)
- **Comprehensive Evaluation**: Cross-validation with multiple performance metrics
- **Standardized Pipeline**: Consistent data preprocessing and feature engineering
- **Comparative Analysis**: Side-by-side algorithm performance comparison

## Data Quality
The datasets demonstrate high-quality characteristics essential for reliable ML training:

- Complete records across all schema columns
- Standardized categorical value formats
- Valid ranges for physical dimensions and pricing
- Sequential unique identifiers for tracking

## Usage
The system processes diamond data through a standardized pipeline:

1. CSV data loading and parsing
2. Feature engineering and categorical encoding
3. Train/validation data splitting
4. Model training across all six algorithms
5. Performance evaluation using MAPE, accuracy, and specificity metrics

## Notes
This project focuses on supervised learning approaches for diamond valuation, providing a comprehensive framework for comparing different ML algorithms on the same standardized dataset. The dual-dataset structure ensures unbiased performance evaluation across all implemented models.
