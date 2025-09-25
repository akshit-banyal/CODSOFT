# 🎬 IMDb Movie Rating Prediction for Indian Cinema

![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-1.5-orange?style=for-the-badge&logo=scikit-learn)
![Pandas](https://img.shields.io/badge/Pandas-2.2-purple?style=for-the-badge&logo=pandas)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

A machine learning project to predict the IMDb rating of Indian movies. This repository contains the complete workflow from data cleaning and feature engineering to model training and evaluation.

---

## 📜 Project Overview

The goal of this project is to analyze the factors that contribute to a movie's rating and build a robust model to predict it. By exploring features like genre, release decade, and audience engagement, we can uncover patterns that define a successful film in the Indian cinema landscape.

---

## 📊 The Dataset

The project utilizes the **IMDb India Movies** dataset, a comprehensive collection of movies from Indian cinema.

* **Source:** [Kaggle - IMDb India Movies](https://www.kaggle.com/datasets/adrianmcmahon/imdb-india-movies)
* **Content:** The dataset contains information on movie names, release year, duration, genre, ratings, votes, directors, and actors.

---

## 🚀 Model & Performance

The **Gradient Boosting** algorithm was selected for its superior performance. We used the `GradientBoostingRegressor` implementation from Scikit-learn for this task.

### Final Model Performance:

* **Mean Absolute Error (MAE):** `0.9436`
* **Root Mean Squared Error (RMSE):** `1.2013`

**Result Analysis:** The model provides a solid baseline performance. An MAE of ~0.94 indicates that, on average, the model's prediction is less than one rating point away from the actual movie rating, which is a reasonably strong result. The RMSE of ~1.2 suggests that while most predictions are close, the model does make some larger errors.

---

## 💡 Key Insights from the Model

The model's **Feature Importance** plot revealed the most influential factors in determining a movie's rating:

1.  **Votes are King 👑:** The **number of votes** a movie receives is by far the most significant predictor.
2.  **The Genre Effect 🎭:** Specific genres like **Drama, Crime,** and **Biography** have a noticeable impact on predicting higher ratings.
3.  **Time Matters ⏳:** The **`Decade`** in which a movie was released is a crucial feature, capturing evolving cinematic styles and audience tastes.

---

## 🛠️ Technologies Used

* Python
* Pandas
* Matplotlib & Seaborn
* Scikit-learn
* Jupyter Notebook

---

## 🔮 Future Scope of Improvement

To further enhance the model's predictive accuracy, the following steps could be explored:

* **Hyperparameter Tuning:** Fine-tune the Gradient Boosting model's parameters to optimize its performance.
* **Advanced Feature Engineering:** Create more complex features, such as calculating average ratings for directors and actors to use as inputs.
* **Explore Other Models:** Experiment with more advanced algorithms like XGBoost, LightGBM, or simple neural networks.

---

## 🔧 How to Use This Repository

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/akshit-banyal/CODSOFT.git](https://github.com/akshit-banyal/CODSOFT.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd CODSOFT
    ```
3.  **Install the required libraries:**
    ```bash
    pip install pandas scikit-learn matplotlib seaborn jupyterlab
    ```
4.  **Launch Jupyter Notebook and open the `.ipynb` file.**
