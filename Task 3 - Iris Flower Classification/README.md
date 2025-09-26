# 🌸 Iris Flower Classification

![NumPy](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white) ![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-3776AB?style=for-the-badge&logo=matplotlib&logoColor=white) ![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=seaborn&logoColor=white)

> This project is a classic machine learning classification problem focused on predicting the species of an Iris flower based on its sepal and petal measurements. The goal is to build and evaluate a model that can accurately distinguish between three different species: `Iris-setosa`, `Iris-versicolor`, and `Iris-virginica`.

---

## 📖 Dataset

The project utilizes the **Iris Flower Dataset**, a classic and well-known dataset in the field of machine learning.

* **Source**: [Kaggle | Iris Flower Dataset](https://www.kaggle.com/datasets/arshid/iris-flower-dataset)
* **Features**: `sepal_length`, `sepal_width`, `petal_length`, `petal_width` (in cm)
* **Target**: `species` (Iris-setosa, Iris-versicolor, Iris-virginica)



---

## 📈 Project Workflow

1.  **Data Loading and Inspection**: The dataset was loaded using `pandas` to inspect its structure, data types, and basic statistics.
2.  **Exploratory Data Analysis (EDA)**: Visualizations like pair plots and heatmaps were created with `seaborn` to understand feature relationships.
3.  **Data Preprocessing**: The categorical target variable (`species`) was encoded into a numerical format using `scikit-learn`.
4.  **Train-Test Split**: The data was divided into training (70%) and testing (30%) sets for unbiased model evaluation.
5.  **Model Training**: A **K-Nearest Neighbors (KNN)** classification model was trained on the prepared data.
6.  **Model Evaluation**: The model's performance was measured using accuracy, a classification report, and a confusion matrix.

---

## 🛠️ Technologies Used

The core libraries used in this project are:
* **NumPy**
* **Pandas**
* **Matplotlib**
* **Seaborn**
* **Scikit-learn**

---

## 📊 Results & Performance

The K-Nearest Neighbors (KNN) model performed exceptionally well, demonstrating high predictive accuracy on the unseen test data.

* **Key Result**: The model achieved a high overall accuracy, successfully classifying the vast majority of the Iris flower samples.
* **Performance Metrics**: The classification report confirmed excellent precision and recall for each species.
* **Visualization**: The confusion matrix heatmap provided a clear visual confirmation of the model's effectiveness, showing very few misclassifications.



---

## 🚀 Getting Started

To run this project on your local machine, follow the steps below.

### **1. Clone the Repository**
```bash
git clone [https://github.com/akshit-banyal/CODSOFT.git](https://github.com/akshit-banyal/CODSOFT.git)
