# 🏋️ Calorie Expenditure Predictor – Kaggle Playground Series S5E5

## 📘 Overview

This repository contains my personal solution to the **2025 Kaggle Playground Series - Season 5, Episode 5 (S5E5)**. As a data enthusiast, I used this opportunity to deepen my machine learning knowledge and build a practical regression model to predict calorie expenditure based on workout data.

This competition is part of Kaggle's monthly Playground Series, aimed at providing lightweight, approachable challenges that help us refine our data science and modelling skills in a fun and engaging way.

🔗 [View the Official Kaggle Competition](https://kaggle.com/competitions/playground-series-s5e5)

---

## 🎯 My Goal

My objective for this competition was to:

* Explore the dataset thoroughly
* Apply effective preprocessing and feature engineering
* Experiment with different machine learning models
* Optimise model performance using the RMSLE metric
* Generate a clean submission for the leaderboard

---

## 📊 Evaluation Metric

The evaluation is based on the **Root Mean Squared Logarithmic Error (RMSLE)**, which is ideal for this problem as it penalises under-predictions more than over-predictions:

$$
\text{RMSLE} = \sqrt{ \frac{1}{n} \sum_{i=1}^{n} \left( \log(\hat{y}_i + 1) - \log(y_i + 1) \right)^2 }
$$

Where:

* $\hat{y}_i$: predicted calories
* $y_i$: actual calories
* $n$: total number of predictions

---

## 📂 Submission Format

Final submissions must follow this format:

```
id,Calories
750000,93.2
750001,27.42
750002,103.8
...etc.
```

---

## 🗓️ Timeline

* **Start:** May 1, 2025
* **Deadline:** May 31, 2025 (11:59 PM UTC)

---

## 📅 My Notebook

The notebook `calorie-expenditure-predictor.ipynb` includes:

* Exploratory data analysis (EDA)
* Feature scaling and encoding
* Model training using regression algorithms
* RMSLE optimisation
* Submission file creation

My approach combined careful preprocessing and model experimentation to balance performance with interpretability.

---

## 📊 Dataset Info

This dataset was synthetically generated to mimic real-world calorie-burning scenarios during workouts. Synthetic data allows us to work with meaningful features while ensuring privacy and data safety.

---

## 🏆 Prizes

Top 3 winners of the competition receive official **Kaggle merchandise**. To promote participation, prizes are awarded once per person across the series.

---

## 📄 Citation

**Walter Reade and Elizabeth Park.** Predict Calorie Expenditure. Kaggle Playground Series S5E5, 2025.
[https://kaggle.com/competitions/playground-series-s5e5](https://kaggle.com/competitions/playground-series-s5e5)

---

## 🙌 A Personal Note

I thoroughly enjoyed working on this project as part of my journey in machine learning and data engineering. It challenged my modelling instincts and gave me space to practise good feature engineering and evaluation techniques.

Feel free to explore the notebook, fork it, or reach out with feedback. I'm always open to learning and collaborating with fellow data scientists.

Cheers,
**Enock Antonio**
