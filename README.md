# Gaussian Naive Bayes Classifier  

## Overview  
This repository implements a **Gaussian Naive Bayes Classifier** for image classification. It processes and classifies a dataset of **28x28 grayscale images** of five different clothing categories. The classifier utilizes training and test data stored in `.pkl` files, performs data preprocessing, and evaluates the model's performance.

## Features  
- **Preprocessing**: Reshapes image data and separates it by categories.  
- **Visualization**: Displays sample images for each category and their averaged representations.  
- **Model Implementation**: Uses Gaussian Naive Bayes to calculate probabilities for classification.  
- **Confusion Matrix**: Builds and prints a confusion matrix to assess performance.  
- **Accuracy Calculation**: Computes the accuracy for both training and test datasets.  

## Requirements  
To run this project, install the required dependencies with:  
```bash
pip install -r requirements.txt
```
## Dataset
- **Train Data**: 24,000 images (28x28 pixels each).
- **Test Data**: 6,000 images (28x28 pixels each).

### Each image belongs to one of five categories:
  1. T-Shirt
  2. Trouser
  3. Coat
  4. Sandal
  5. Ankle-Boot

## How It Works
1. **Data Loading**: Loads training and test datasets from `.pkl` files.
2. **Visualization**: Displays one sample image per category and the average image of each category.
3. **Variance Calculation**: Computes variance for Gaussian distribution.
4. **Classification**: Implements a Gaussian function to calculate likelihoods for classification.
5. **Confusion Matrix**: Builds and prints a matrix to show classification results.

## Example Results
- **Accuracy (Train)**: XX%
- **Accuracy (Test)**: XX%
- **Confusion Matrix**:
  ```bash
  T-Shirts  Trouser  Coat  Sandal  Ankle-Boot
  XX        XX       XX    XX      XX
  XX        XX       XX    XX      XX
  ...
  ```

## Usage
Run the `GaussianNaiveBayesClassifier.ipynb` notebook in Jupyter or any compatible environment:
```bash
jupyter notebook GaussianNaiveBayesClassifier.ipynb
```

## Output
- Visualization of example images and averages.
- Accuracy metrics for training and test data.
- Neatly formatted confusion matrix.
