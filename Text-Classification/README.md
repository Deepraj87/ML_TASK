
# Naive Bayes Text Classifier for 20 Newsgroups Dataset

## 📖 Overview
This project involves developing a Naive Bayes text classifier to categorize documents into their respective newsgroups using the 20 Newsgroups dataset. The main steps include data preprocessing, model training, evaluation, and visualization of results.

## 📊 Dataset
The 20 Newsgroups dataset is a collection of approximately 20,000 newsgroup documents, which are divided across 20 different newsgroups. These newsgroups are categorized into six main topics: computers, recreation, science, religion, politics, and miscellaneous. Each document in the dataset is labeled with one of the 20 newsgroups, making it a widely used benchmark for text classification and natural language processing (NLP) tasks.

## 🌟 Features

**1. Text Preprocessing:**

- Tokenization, stop word removal, and TF-IDF vectorization.
- Handles raw text conversion into numerical features.

**2. Model Training:**

- Uses Naive Bayes classifier, suitable for text data.
- Efficiently trains on the preprocessed dataset.

**3. Model Evaluation:**

- Computes accuracy, precision, recall, and F1 score.
- Generates and visualizes the confusion matrix using a heatmap.

**4. Documentation:**

- Detailed README with setup instructions, usage, and evaluation metrics.
- Organized directory structure for reproducibility.

## 🚀Setup and Installation

**1. Clone my repository:**

```bash
  git clone https://github.com/Deepraj87/ML_TASKS.git

```
**2.Install the required dependencies:**
```bash
  pip install -r requirements.txt
```

## 🤝How to Run

**1. Preprocess the Data:**
```bash
  python src/Data Preprocessing.ipynb
```
This script will load the 20 Newsgroups dataset, preprocess it, and split it into training and testing sets.

**2. Train the Model:**

```bash
  python src/Model_Training.ipynb
```

This script trains a Naive Bayes model using the training data .

**3. Evaluate the Model:**
```bash
  python src/Model Evaluation.ipynb
```

This script evaluates the trained model on the test data, computes various performance metrics, and plots the confusion matrix.
## 📊 Evaluation Metrics
The following evaluation metrics are computed: 

- Accuracy: Overall correctness of the model.
- Precision: Proportion of true positive results among all positive predictions.
- Recall: Proportion of true positive results among all actual positives.
- F1 Score: Harmonic mean of precision and recall.
## 🧠 Confusion Matrix
The confusion matrix is plotted and displayed using a heatmap to visualize the model's performance across different classes.

## 📚 Lessons Learned
Key lessons learned from this project include:

- Practical application of machine learning algorithms.
- Evaluation and selection of appropriate metrics based on project goals.
- Implementation of machine learning models for practical applications.
