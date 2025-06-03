# 🚀 Falcon 9 First Stage Landing Prediction – Capstone Project

This project is part of the **IBM Data Science Professional Certificate**. The goal is to predict whether the **Falcon 9 first stage will land successfully**. The project is divided into four modules, each focusing on a specific part of the workflow:

---

## 📁 Module Breakdown

### 📂 Module 1 – Collecting Launch Data using SpaceX API
- Uses the SpaceX API to collect historical launch data.
- Cleans and transforms the data.
- Outputs a cleaned CSV file `dataset_part_1.csv`.

### 📂 Module 2 – Exploratory Data Analysis (EDA)
- Analyzes trends and patterns in the Falcon 9 launch data.
- Uses visualizations to understand correlations and landing outcomes.

### 📂 Module 3 – Feature Engineering
- Transforms the data into suitable features for machine learning.
- Normalizes and encodes relevant columns.
- Creates training and test datasets.

### 📂 Module 4 – Machine Learning Model Development
- Trains and evaluates various classification models.
- Compares model performance to identify the best predictor for landing outcomes.

---

## 🛠️ How to Run the Project

1. Open each module folder in Jupyter Notebook or any Python IDE.
2. Run the notebooks **in order**: Module 1 → Module 4.
3. Ensure required packages (`pandas`, `numpy`, `matplotlib`, `scikit-learn`, etc.) are installed.
4. For Module 1, make sure you're connected to the internet to call the SpaceX API.

---

## 📦 Requirements

- Python 3.x
- Jupyter Notebook
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `requests`

---

## 📄 Output Files

- `dataset_part_1.csv` – Cleaned data from API
- `model_results.csv` (optional) – Model comparison summary
