# DASS: Depression, Anxiety, and Stress Survey Analysis

This project involves the analysis of survey data to identify potential indicators of **Depression**, **Anxiety**, and **Stress (DASS)** using unsupervised learning techniques, specifically **K-Means clustering**. The dataset includes responses to a variety of mental health, lifestyle, and demographic questions.

---

## 📊 Features & Methodology

- **Data Cleaning & Preprocessing**
  - Normalization of open-text responses using string cleaning, mapping, and NLP (sentence embeddings + clustering).
  - Encoding of categorical variables.
  - Handling of missing or ambiguous responses.

- **Clustering**
  - Used `KMeans` clustering to group respondents into two categories: likely to have mental health conditions or not.
  - All features are standardized using `StandardScaler`.

- **Visualization**
  - PCA (Principal Component Analysis) used for 2D visualization of clusters.
  - Plots generated using `matplotlib`.

---

## 🧠 Technologies Used

- Python 3.x
- pandas, numpy
- scikit-learn
- sentence-transformers
- matplotlib, seaborn

---

