# 🎧 Clustering of Music Listeners Based on Psychological Impact and Music Preferences

This project implements **K-Means Clustering** to analyze and group music listeners based on psychological indicators and listening habits. The data was taken from a survey of music listeners and includes variables like mental health scores, hours of music listened per day, and tempo preferences.

---

## 📁 Dataset

The dataset used is `mxmh_survey_results.csv`, which contains responses from 700+ individuals.

Key features used:
- **BPM** (Beats Per Minute of favorite songs)
- **Anxiety**, **Depression**, **Insomnia** scores (scale 0–10)
- **Hours per day** listening to music

---

## ⚙️ Methods

1. Data cleaning: remove missing values
2. Feature selection
3. Standardization using `StandardScaler`
4. Clustering using **K-Means** algorithm (3 clusters)
5. Visualization using scatter plot (`matplotlib`)

---

## 📊 Result Visualization

A scatter plot shows the clustering result based on **Anxiety** and **Depression** scores.  
Each color represents a different cluster formed by the K-Means algorithm.

> 🖼️ See: `hasil_clustering.png`

---

## 🧪 Libraries Used

- Python 3.x
- `pandas`
- `matplotlib`
- `scikit-learn`

---

## 🚀 How to Run

Make sure you have Python and required libraries installed.  
To install dependencies:

```bash
pip install -r requirements.txt
