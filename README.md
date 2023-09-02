## Introduction

This repository contains the final project for the Machine Learning course. The goal of the project was to develop a model that predicts whether a given text is written by a male or a female author. The project involved various steps, including data preprocessing, feature extraction, model training, and evaluation.

## Dataset

The dataset used for this project consisted of texts along with their corresponding gender labels (male or female). The texts were preprocessed to remove numbers, special characters, and English words, leaving behind only the essential content.

## Approach

### Data Cleaning

Before training the models, the text data underwent preprocessing to ensure its quality and uniformity. Numbers, special characters, and English words were removed to focus solely on the essential content.

### Feature Extraction

The CountVectorizer technique was employed to transform the text data into numerical format suitable for machine learning algorithms. This process converted the text into a matrix of token counts, effectively representing the frequency of words in each text.

### Models Explored

Four different machine learning models were utilized to predict the gender of the authors based on the transformed text data:

1. **Multinomial Naive Bayes (MultinomialNB):** This probabilistic model is often used for text classification tasks due to its simplicity and effectiveness in dealing with discrete features.

2. **Decision Tree Classifier:** Decision trees divide the feature space into regions based on the features' values, allowing the model to make predictions through a series of decisions.

3. **K-Nearest Neighbors (KNN) Classifier:** KNN makes predictions based on the majority class of its k-nearest neighbors in the feature space.

4. **Linear Support Vector Classifier (LinearSVC):** LinearSVC seeks to find the hyperplane that best separates the classes in the feature space, making it suitable for binary classification tasks.

### Model Evaluation

The performance of each model was evaluated using a variety of metrics, including accuracy, precision, recall, and F1-score. The F1-score was especially important as it provides a balance between precision and recall, which is crucial for our text classification problem.

## Conclusion

In this project, I successfully developed models to predict the gender of authors based on text data. Through data preprocessing, feature extraction, and model training, I explored the effectiveness of MultinomialNB, DecisionTreeClassifier, KNeighborsClassifier, and LinearSVC models. The project provided valuable insights into the application of machine learning techniques to text classification tasks.

Feel free to explore the code and the accompanying documentation to gain a deeper understanding of the steps and processes involved in this project.
