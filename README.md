# Gender Predictor

A machine learning project built in Python that predicts a person's gender based on their height and weight[cite: 3]. 

## Overview
This repository contains a Jupyter Notebook that processes physical metrics to train a classification model[cite: 3]. The project covers the full data science pipeline, from exploratory data analysis and data cleaning to model training and performance evaluation[cite: 3].

## Key Features & Workflow
* **Data Cleaning:** Identified and removed severe outliers in the dataset (e.g., erroneous heights up to 3050 and weights up to 485) by setting realistic thresholds for human metrics[cite: 3].
* **Exploratory Data Analysis (EDA):** Utilized Seaborn and Matplotlib to create boxplots comparing the distributions of height and weight across genders[cite: 3].
* **Machine Learning Models:** Experimented with a K-Nearest Neighbors (KNN) classifier before finalizing a **Random Forest Classifier**[cite: 3]. 
* **Model Evaluation:** The Random Forest model achieved an **87.3% accuracy rate** on the test data[cite: 3]. The project includes a visualized confusion matrix breaking down the model's true positive and false positive prediction rates[cite: 3].
* **Interactive Prediction:** Features a custom Python function (`predict_gender`) that allows users to input custom height and weight values via the command line to get a real-time gender prediction[cite: 3].

## Tech Stack
* **Python** (Jupyter Notebook)[cite: 3]
* **Pandas** (Data manipulation and cleaning)[cite: 3]
* **Seaborn & Matplotlib** (Data visualization)[cite: 3]
* **Scikit-Learn** (Model training, Random Forest, KNN, and Confusion Matrix metrics)[cite: 3]

## How to Use
1. Clone this repository to your local machine.
2. Ensure you have the required libraries installed (`pandas`, `matplotlib`, `seaborn`, `scikit-learn`).
3. Open the Jupyter Notebook and run all cells to clean the data and train the classifier.
4. Run the `predict_gender(model_0)` function at the bottom of the notebook and enter custom height and weight values when prompted to test the model yourself[cite: 3].
