# 🚀 SpaceX Falcon 9 First Stage Landing Prediction
### *IBM Data Science Professional Certificate — Capstone Project*

This repository contains my complete end-to-end **IBM Data Science Capstone Project**, where I analyze SpaceX Falcon 9 launch data and build a **machine learning model** to predict whether the **first stage successfully lands**. Reusability of the Falcon 9 booster significantly reduces launch costs, making landing prediction a key factor in cost optimization.

This project integrates **data collection, web scraping, data wrangling, EDA, interactive visualizations, and machine learning**.
---

## 📁 Project Structure

```
SpaceX-Falcon9-Landing-Prediction/
│── notebooks/
│   ├── spacex_data_collection_api.ipynb
│   ├── webscraping.ipynb
│   ├── edadataviz.ipynb
│   ├── SpaceX_Machine Learning Prediction.ipynb
│── datasets/
│   ├── spacex_launches_cleaned.csv
│   ├── falcon9_launches_cleaned.csv
│── README.md
```

---

## 📘 Notebooks Overview

### 1️⃣ spacex_data_collection_api.ipynb
**Purpose:** Collect SpaceX launch data using the official SpaceX REST API.  
**Key Steps:**  
- API request & JSON extraction  
- Parsing launch metadata  
- Creating DataFrame and cleaning fields  
- Exporting dataset for downstream analysis  

**Output:** `spacex_launches_cleaned.csv`

---

### 2️⃣ webscraping.ipynb
**Purpose:** Scrape Falcon 9 launch records from **Wikipedia**.  
**Key Steps:**  
- Extract multi-level HTML tables  
- Flatten column names  
- Merge scraped + API data  
- Export structured CSV  

**Output:** `falcon9_launches_cleaned.csv`

---

### 3️⃣ edadataviz.ipynb
**Purpose:** Perform detailed **Exploratory Data Analysis (EDA)**.  
**Highlights:**  
- Launch outcome distribution  
- Orbit vs landing success  
- Booster version analysis  
- Scatter plots, bar charts, heatmaps  

**Tools:** Pandas, Matplotlib, Seaborn, Plotly

---

### 4️⃣ SpaceX_Machine Learning Prediction.ipynb
**Purpose:** Build ML models to predict **booster landing success**.  
**Models Used:**  
- Logistic Regression  
- KNN  
- SVM  
- Decision Tree  
- GridSearchCV for parameter tuning  

**Metrics:**  
- Accuracy  
- Confusion Matrix  
- Classification Report  

**Outcome:** Achieved high accuracy and identified best-performing model.

---

## 🧠 Machine Learning Workflow
✔ Data Cleaning  
✔ Feature Engineering  
✔ One-hot Encoding  
✔ Train / Test Split  
✔ Model Training  
✔ Hyperparameter Tuning  
✔ Model Comparison  
✔ Final Prediction Output  

---

## 🛠️ Technologies Used
- Python 3  
- Pandas, NumPy  
- Matplotlib, Seaborn, Plotly  
- Scikit-Learn  
- Requests  
- BeautifulSoup  
- Jupyter Notebook / Google Colab  

---

## 🎯 Project Goal
To accurately predict whether SpaceX Falcon 9 first stage will **successfully land**, using real launch data and ML models. This work demonstrates skills in data collection, scraping, wrangling, visualization, and predictive modeling.

---

## 📜 Certification Note
This repository is part of my **IBM Data Science Professional Certificate – Capstone Project**, fulfilling the official capstone requirements.

---

## ▶️ How to Run the Project

### 1. Clone the repo:
```
git clone https://github.com/nkale882/SpaceX-Falcon-9-Landing-Prediction.git
```

### 2. Install dependencies:
```
pip install -r requirements.txt
```

### 3. Open notebooks:
```
jupyter notebook
```

---

## 💬 Feedback
Open an issue for suggestions or improvements.  
Happy learning! 🚀
