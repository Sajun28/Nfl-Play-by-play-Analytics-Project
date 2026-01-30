# 🏈 NFL Play-by-Play Analytics: Touchdown Probability & Play Strategy Analysis

## 📌 Project Topic

**Analyzing Touchdown Probability Based on Play Type and Game Situations Using NFL Play-by-Play Data**

---

## 🧠 Project Overview

This project focuses on analyzing NFL play-by-play data to understand how different game situations and offensive play types influence the probability of scoring a touchdown. By leveraging exploratory data analysis (EDA), statistical correlations, and machine learning techniques, the project extracts meaningful insights into play-calling strategies such as rushing vs passing, field position impact, and down-and-distance scenarios.

The goal is to demonstrate practical data analytics skills using real-world sports data and present insights in a clear, recruiter-friendly manner suitable for GitHub and LinkedIn.

---

## 🎯 Objectives

* Analyze touchdown probability based on **rush vs pass plays**
* Study the impact of **down, yards to go, field position, and time remaining**
* Visualize relationships using **correlation heatmaps and bar charts**
* Build and interpret a **machine learning model** for play outcome prediction
* Present clean, well-documented, and reproducible analysis

---

## 📂 Dataset

* **Source:** NFL Play-by-Play Dataset
* **Type:** Structured tabular data
* **Granularity:** One row per play

### Key Features Used

* `down`
* `ydstogo`
* `yardline_100`
* `time_remaining_sec`
* `rush_attempt`
* `pass_attempt`
* `touchdown`
* `EPA` (Expected Points Added)

---

## 🛠️ Tools & Technologies

* **Programming Language:** Python 3
* **Libraries:**

  * pandas
  * numpy
  * matplotlib
  * seaborn
  * scikit-learn
* **Environment:** Jupyter Notebook / Google Colab

---

## 🔍 Methodology

### 1️⃣ Data Cleaning

* Handled missing values
* Removed irrelevant columns
* Converted categorical features where necessary
* Ensured numeric consistency for modeling

### 2️⃣ Exploratory Data Analysis (EDA)

* Correlation heatmaps to identify key relationships
* Bar plots comparing touchdown probability for rush vs pass plays
* Distribution analysis for game situation variables

### 3️⃣ Feature Engineering

* Derived game-context features such as score difference and goal-to-go situations
* Selected relevant numeric features for modeling

### 4️⃣ Modeling

* Trained a **RandomForestClassifier** to predict play outcomes
* Evaluated model performance using ROC-AUC and feature importance

### 5️⃣ Visualization

* 2×2 correlation heatmaps
* Feature importance plots
* Touchdown probability comparison charts

---

## 📊 Key Insights

* Passing plays generally show a **higher touchdown probability** than rushing plays
* Field position (`yardline_100`) strongly influences scoring chances
* Shorter yards-to-go situations increase touchdown likelihood
* Game context plays a critical role in offensive decision-making

---

## 📈 Results

* Clear visualization of play-type effectiveness
* Interpretable feature importance from tree-based models
* Actionable insights aligned with real NFL strategies

---

## 📁 Project Structure

```
NFL-Play-By-Play-Analytics/
│
├── data/
│   └── nfl_play_by_play.csv
│
├── notebooks/
│   └── analysis.ipynb
│
├── images/
│   └── visualizations.png
│
├── requirements.txt
└── README.md
```

---

## 🚀 How to Run the Project

1. Clone the repository

```bash
git 

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Run the notebook

```bash
jupyter notebook
```

---

## 🎯 Future Improvements

* Add advanced models (XGBoost, LightGBM)
* Perform red-zone specific analysis
* Incorporate player-level efficiency metrics
* Deploy results using Streamlit or Flask

---

## 👤 Author

**Sachin**
Aspiring Data Analyst / Machine Learning Enthusiast

---

## ⭐ Acknowledgements

* NFL Play-by-Play Data Contributors
* Open-source Python community

---

## 📌 Note

This project is created for educational and portfolio purposes to demonstrate data analytics and machine learning skills using real-world sports data.
