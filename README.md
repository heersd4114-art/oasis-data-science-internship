# Oasis Infobyte Data Science Internship - Project Portfolio

![Oasis Infobyte](https://img.shields.io/badge/Oasis%20Infobyte-Data%20Science%20Internship-blue?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3.11-yellow?style=for-the-badge&logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-orange?style=for-the-badge&logo=jupyter)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-Machine%20Learning-F7931E?style=for-the-badge&logo=scikit-learn)

Welcome to my project portfolio for the **Oasis Infobyte Data Science Internship**. This repository contains 5 complete, end-to-end Machine Learning and Data Analysis tasks demonstrating proficiency in Exploratory Data Analysis (EDA), Data Preprocessing, Natural Language Processing (NLP), and Predictive Modeling.

---

## 📂 Project Structure & Tasks

### 🌸 [Task 1: Iris Flower Classification](Task1_Iris_Classification.ipynb)
- **Objective:** Train a classifier to identify the species of an iris flower (*Setosa*, *Versicolor*, or *Virginica*).
- **Tech Stack:** `scikit-learn`, `pandas`, `seaborn`
- **Highlights:** Utilized the built-in Iris dataset. Analyzed feature separability using pairplots and box plots. Compared Logistic Regression, K-Nearest Neighbors (KNN), Decision Trees, and Random Forests.
- **Result:** Models performed with exceptional accuracy (~100% on scaled components), proving the dataset's high separability through petal width/length.

### 📈 [Task 2: Unemployment Analysis in India](Task2_Unemployment_Analysis.ipynb)
- **Objective:** Analyze India's unemployment dataset to measure the dramatic economic impacts caused by the COVID-19 pandemic.
- **Tech Stack:** `pandas`, `matplotlib`, `seaborn`
- **Highlights:** Cleaned raw data and tracked Month-over-Month patterns using time-series line charts across multiple regions and states.
- **Result:** Visualized the nationwide spike in unemployment starting April 2020. Evaluated Pre-COVID vs. Post-COVID averages, identifying a 40.4% surge in unemployment rates.

### 🚗 [Task 3: Car Price Prediction](Task3_Car_Price_Prediction.ipynb)
- **Objective:** Build a regression model that strictly predicts used vehicle selling prices based on age, mileage, and present showroom price.
- **Tech Stack:** `pandas`, `sklearn.ensemble`, `seaborn`
- **Highlights:** Engineered variables like `Car_Age` and simplified categorical variables using Label Encoding. 
- **Result:** The Gradient Boosting Regressor achieved an impressive **R² = 0.748**, pinpointing `Present_Price` and `Car_Age` as the fundamental depreciation metrics.

### 📧 [Task 4: Email Spam Detection](Task4_Spam_Detection.ipynb)
- **Objective:** Build a robust NLP binary classification pipeline distinguishing malicious spam messages from legitimate "ham" messages.
- **Tech Stack:** `nltk`, `TF-IDF Vectorizer`, `WordCloud`, `Support Vector Machines`
- **Highlights:** Applied advanced text preprocessing (stemming, lowercasing, stop-word removal). Formulated a visual distinction of terminology via custom WordClouds!
- **Result:** Attained a massive **98.1% accuracy** using a Support Vector Machine classifier, achieving an exceptionally high spam *precision* metric preventing false positives.

### 📊 [Task 5: Sales Prediction Using Python](Task5_Sales_Prediction.ipynb)
- **Objective:** Interpret multi-channel marketing campaigns (TV, Radio, Newspaper) to predict unit product sales.
- **Tech Stack:** `Polynomial Regression`, `Random Forest`, `seaborn`
- **Highlights:** Designed a feature correlation matrix proving which advertising sector performs best.
- **Result:** Analyzed regression coefficients mapped out via degrees. *TV impact heavily outperformed Newspaper impact*, delivering an ultimate **R² score of 0.987**.

---

## 🛠️ Setup & Installation

To run these notebooks locally, ensure you have Python 3.8+ installed, then clone the repository:

```bash
git clone https://github.com/heersd4114-art/oasis-data-science-internship.git
cd oasis-data-science-internship
```

Install the required dependencies:

```bash
pip install pandas scikit-learn matplotlib seaborn nltk wordcloud jupyter
```

*Note: For Task 4, NLTK stopwords and punkt tokenizers may need manual downloading using `nltk.download()` in Python.*

## 📜 Certificate & Verification
These independent analysis tasks are submitted toward the completion of the Data Science internship program curated by **Oasis Infobyte**. 

---
*Created with ❤️ by an aspiring Data Scientist.*
