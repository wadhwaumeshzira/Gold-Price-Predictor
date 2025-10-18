# Gold Price Predictor

![Python](https://img.shields.io/badge/Python-3.12-blue?logo=python\&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-0.24-orange?logo=scikit-learn\&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-1.5-brightgreen?logo=pandas\&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7-red?logo=matplotlib\&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)

Predict **gold prices** using historical data with a **Random Forest regression** model. This project demonstrates **time series analysis, regression modeling, data visualization**, and **model evaluation** using standard metrics.

---

## 🚀 Features

* Predicts gold prices based on historical trends.
* Implements **Random Forest Regression** for accurate prediction.
* Visualizes **actual vs predicted prices** with clear line plots.
* Evaluates model performance with **R² Score, MAE, and RMSE**.

---

## 🛠️ Tech Stack

* **Python**
* **Pandas**, **NumPy**
* **Scikit-learn**
* **Matplotlib**, **Seaborn**

---

## 📈 Usage

### 1. Clone the repository

```bash
git clone <repo_link>
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Load the dataset

Ensure your dataset (CSV) contains at least the following columns:

* `Date`
* `Gold`

### 4. Run the Jupyter notebook

```bash
jupyter notebook Gold_Price_Prediction.ipynb
```

### 5. Preprocess the data

* Convert `Date` column to datetime (if needed).
* Set `Date` as index.
* Create features for prediction (e.g., previous day's gold price).

### 6. Train the model

* Split data into training and testing sets.
* Use **Random Forest Regression** and fit on training data.

### 7. Make predictions

* Predict gold prices on the test data.
* Compare predicted vs actual prices.

### 8. Evaluate performance

* Compute **R² Score, MAE, and RMSE**.
* Visualize **actual vs predicted prices** using Matplotlib.

### 9. Analyze results

* Check prediction accuracy.
* Tune hyperparameters if necessary.

---

## 🧮 Evaluation Metrics

* **R² Score** – How well the model explains variance in the data.
* **Mean Absolute Error (MAE)** – Average prediction error.
* **Root Mean Squared Error (RMSE)** – Overall deviation from actual prices.

---

## 📉 Visualization

The notebook includes **line plots comparing actual vs predicted gold prices** to visually assess prediction accuracy.

---


## ✨ Author

**Umesh Kumar** – B.Tech IT, IIIT Bhopal
[LinkedIn](https://www.linkedin.com/in/umesh-kumar) | [GitHub](https://github.com/umesh-kumar)

---
