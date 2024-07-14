
# 🚀 K-Nearest Neighbors Image Classification using Iris Dataset

Welcome to the K-Nearest Neighbors (KNN) Image Classification project! This project aims to classify images from the Iris dataset using the KNN algorithm. Dive into the world of image classification with this exciting project!

## 🌟 Overview

In this project, we'll develop an image classification system using KNN to classify images from the Iris dataset, which consists of three iris species with 50 samples each as well as some properties about each flower. One flower species is linearly separable from the other two, but the other two are not linearly separable from each other. The project is organized into distinct phases:

1. **Data Preprocessing**: Load, normalize, and reshape the CIFAR-10 dataset.
2. **Model Training**: Train the KNN classifier using Euclidean distance.
3. **Model Evaluation**: Evaluate the model's performance on test data.

## 🎯 Objective

Our goal is to create a robust image classification system that can accurately classify new images into one of the iris classes.

## 📋 Prerequisites

Before you begin, ensure you have the following:

- Python 3.6 or higher
- Git
- pip (Python package installer)

## 🔧 Setup

**1. Clone my repository:**

```bash
  git clone https://github.com/Deepraj87/ML_TASKS.git

```
**2.Install the required dependencies:**
```bash
  pip install -r requirements.txt
```

## 🌍 Project Structure

```plaintext
KNN-Image-Classification/
├── Data/
|   ├── Iris.csv
|
├── models/  
|   ├── Model Evaluation.ipynb
│   ├── knn_model.joblib
|   ├── training_model.ipynb
|
├── src/
│   ├── preprocess.ipynb
│   ├── test_data.npy
│   ├── test_labels.npy
│   ├── train_data.npy
│   ├── train_labels.npy
|
├── README.md
├── requirements.txt
├── setup.py


```
- data/: Directory containing the preprocessed data files.
- models/: Directory containing the trained model file.
- src/: Directory containing the Python scripts for preprocessing, training and downloading files.
- requirements.txt: List of required Python packages.
- README.md: This is readme file.

## 🚀 Usage

**1. Preprocess the Data:**
```bash
  python src/preprocess.ipynb
```
This script will load the Iris dataset, preprocess it, and split it into training and testing sets.

**2. Train the Model:**

```bash
  python models/training_model.ipynb
```

This script trains a KNN Model using the training data .

**3. Evaluate the Model:**
```bash
  python models/Model Evaluation.ipynb
```
## 📊 Evaluation Metrics
Our model is evaluated using the following metrics:

- Accuracy: The proportion of correct predictions out of all predictions made.
- Classification Report: Provides precision, recall, and F1-score for each class.


## 📈 Results
After training and evaluating the model, you can expect the results to look something like this:
```yaml
Accuracy: 100 %
Classification Report:
                precision    recall  f1-score   support

      setosa       1.00      1.00      1.00        10
  versicolor       1.00      1.00      1.00         9
   virginica       1.00      1.00      1.00        11

    accuracy                           1.00        30
   macro avg       1.00      1.00      1.00        30
weighted avg       1.00      1.00      1.00        30

```

## 🤝 Contributing
Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch: git checkout -b feature-branch-name.
3. Make your changes and commit them: git commit -m 'Add some feature'.
4. Push to the branch: git push origin feature-branch-name.
5. Submit a pull request.

## 🎉 Happy Coding! 🎉

We hope you enjoy working on this project as much as we enjoyed creating it. If you have any questions or need further assistance, feel free to open an issue or contact us directly.

