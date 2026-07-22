<div align="center">

# 🚗 Car Price Prediction Using Machine Learning

### 🚀 Data-Driven Used Car Price Analysis & Prediction

<img src="https://img.shields.io/badge/Python-3.12-blue?logo=python">
<img src="https://img.shields.io/badge/Pandas-Data%20Analysis-green?logo=pandas">
<img src="https://img.shields.io/badge/NumPy-Scientific%20Computing-blue?logo=numpy">
<img src="https://img.shields.io/badge/Matplotlib-Visualization-orange">
<img src="https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?logo=scikitlearn">
<img src="https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter">
<img src="https://img.shields.io/badge/License-MIT-success">

### 📊 Explore Vehicle Features, Analyze Price Trends & Predict Used Car Prices

*A complete machine learning regression project that analyzes used car data, performs data preprocessing and feature engineering, explores vehicle price trends, compares multiple machine learning models, and predicts car selling prices.*

---

</div>

# 📖 Overview

**Car Price Prediction Using Machine Learning** is a data-driven project focused on analyzing and predicting the selling prices of used cars.

The project uses Python and popular data science libraries to transform raw vehicle data into meaningful insights and machine learning predictions.

The analysis focuses on:

* 🚗 Car name and vehicle analysis
* 💰 Present price and selling price comparison
* 📅 Vehicle age and depreciation
* 🛣️ Kilometers driven analysis
* ⛽ Fuel type comparison
* ⚙️ Transmission analysis
* 👤 Previous owner analysis
* 🤖 Machine Learning-based car price prediction

---

# ✨ Key Features

✅ Data Cleaning and Preprocessing

✅ Exploratory Data Analysis

✅ Vehicle Age Feature Engineering

✅ Categorical Data Encoding

✅ Train-Test Data Splitting

✅ Multiple Regression Models

✅ Model Performance Comparison

✅ Actual vs Predicted Price Analysis

✅ Data Visualization

✅ Used Car Price Prediction

---

# 📊 Dataset Information

The project uses a used car dataset containing information about vehicle features and selling prices.

| Feature       | Description               |
| ------------- | ------------------------- |
| Car_Name      | Name of the car           |
| Year          | Manufacturing year        |
| Selling_Price | Target selling price      |
| Present_Price | Current market price      |
| Driven_kms    | Kilometers driven         |
| Fuel_Type     | Petrol, Diesel, or CNG    |
| Selling_type  | Dealer or Individual      |
| Transmission  | Manual or Automatic       |
| Owner         | Number of previous owners |

### 🎯 Target Variable

```text
Selling_Price
```

The machine learning model predicts the selling price of a used car based on its features.

---

# ⚙️ Feature Engineering

Vehicle age is calculated using the manufacturing year.

```text
Car Age = Current Year - Manufacturing Year
```

This helps the model understand the relationship between:

```text
Vehicle Age
     │
     ▼
Depreciation
     │
     ▼
Resale Value
```

---

# 📈 Analysis Performed

## 1️⃣ Price Analysis

Analyzes the relationship between present market price and selling price.

```text
Present Price
      │
      ▼
Market Value
      │
      ▼
Selling Price
```

---

## 2️⃣ Vehicle Age Analysis

Analyzes how the age of a vehicle affects its resale value.

Older vehicles generally experience greater depreciation.

---

## 3️⃣ Kilometers Driven Analysis

Analyzes the impact of vehicle usage on selling price.

```text
Higher Kilometers
        │
        ▼
More Usage
        │
        ▼
Possible Price Reduction
```

---

## 4️⃣ Fuel Type Analysis

The project compares:

* ⛽ Petrol
* 🛢️ Diesel
* 🌱 CNG

to understand their impact on used car prices.

---

## 5️⃣ Transmission Analysis

The project analyzes the price difference between:

* ⚙️ Manual Vehicles
* 🚘 Automatic Vehicles

---

# 🧠 Machine Learning Models

The project uses multiple regression algorithms to predict car prices.

### 📌 Linear Regression

Used as a baseline machine learning model.

### 🌳 Decision Tree Regressor

Learns decision rules from vehicle features.

### 🌲 Random Forest Regressor

Combines multiple decision trees to improve prediction performance.

### 🚀 Gradient Boosting Regressor

Builds models sequentially to reduce prediction errors.

---

# 🔄 Machine Learning Workflow

```text
        Car Dataset
             │
             ▼
      Data Preprocessing
             │
             ▼
      Feature Engineering
             │
             ▼
    Categorical Encoding
             │
             ▼
        Train-Test Split
             │
             ▼
      Machine Learning Models
             │
      ┌──────┼──────────┐
      ▼      ▼          ▼
 Linear  Random     Gradient
Regression Forest    Boosting
             │
             ▼
       Model Evaluation
             │
             ▼
      Best Model Selection
             │
             ▼
       Car Price Prediction
```

---

# 📊 Model Evaluation

The models are evaluated using:

| Metric   | Purpose                                  |
| -------- | ---------------------------------------- |
| MAE      | Measures average prediction error        |
| MSE      | Penalizes large prediction errors        |
| RMSE     | Measures prediction error in price units |
| R² Score | Measures model performance               |

The best-performing model is selected based on its evaluation results.

---

# 📊 Data Visualization

The project includes:

📈 Selling Price Distribution

💰 Present Price vs Selling Price

📅 Car Age vs Selling Price

🛣️ Driven Kilometers vs Selling Price

⛽ Fuel Type Price Comparison

⚙️ Transmission Price Comparison

📊 Actual vs Predicted Price

🏆 Machine Learning Model Comparison

---

# 🛠️ Technology Stack

## 💻 Programming Language

* Python 3

## 📊 Data Analysis

* Pandas
* NumPy

## 📈 Data Visualization

* Matplotlib

## 🤖 Machine Learning

* Scikit-Learn

## 📓 Development Environment

* Jupyter Notebook
* VS Code

---

# 🏗️ Project Structure

```text
Car-Price-Prediction/
│
├── 📄 car data.csv
├── 📓 car prediction.ipynb
├── 📄 requirements.txt
├── 📖 README.md
│
└── 📊 visualizations/
    ├── price_distribution.png
    ├── present_vs_selling_price.png
    ├── car_age_analysis.png
    └── model_comparison.png
```

---

# ⚙️ Installation

## 1️⃣ Clone Repository

```bash
git clone https://github.com/Priyadharshinipalanisami/Car-Price-Prediction.git
```

---

## 2️⃣ Move into Project Folder

```bash
cd Car Prediction
```

---

## 3️⃣ Install Requirements

```bash
pip install -r requirements.txt
```

---

# 📦 Requirements

```text
pandas
numpy
matplotlib
scikit-learn
jupyter
```

---

# ▶️ Run the Project

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
car prediction.ipynb
```

Run all cells to perform:

```text
Data Cleaning
      ↓
Data Exploration
      ↓
Feature Engineering
      ↓
Data Visualization
      ↓
Machine Learning
      ↓
Model Evaluation
      ↓
Car Price Prediction
```

---

# 🎯 Key Insights

📈 Present price has a strong relationship with selling price.

📅 Vehicle age affects resale value through depreciation.

🛣️ Higher kilometers driven can reduce the resale price.

⛽ Fuel type influences used car market value.

⚙️ Transmission type can affect customer preferences and pricing.

🤖 Machine learning can effectively support real-world vehicle price prediction.

📊 Data analysis provides valuable insights into the used car market.

---

# 🚀 Future Improvements

✅ Add Brand Goodwill Score

✅ Add Horsepower

✅ Add Mileage

✅ Add Engine Capacity

✅ Add Torque

✅ Add Safety Rating

✅ Add Number of Airbags

✅ Add Service History

✅ Add Accident History

✅ Add Vehicle Condition

✅ Build an Interactive Streamlit Dashboard

✅ Deploy the Model as a Web Application

✅ Add Real-Time Car Price Prediction

✅ Create a Mobile Application

---

# 🎯 Learning Outcomes

✔ Data Cleaning

✔ Exploratory Data Analysis

✔ Feature Engineering

✔ Categorical Data Encoding

✔ Regression Machine Learning

✔ Model Training

✔ Model Evaluation

✔ Data Visualization

✔ Price Prediction

✔ Real-World Machine Learning Application

---

# 👨‍💻 Author

## **Priyadharshini P**

🎓 MCA Student

💻 Data Science & Machine Learning Enthusiast

📊 Python Developer

🚀 Interested in Artificial Intelligence and Data Analytics

---

# 🤝 Acknowledgements

* ❤️ Python
* ❤️ Pandas
* ❤️ NumPy
* ❤️ Matplotlib
* ❤️ Scikit-Learn
* ❤️ Jupyter Notebook

---

# 📜 License

This project is licensed under the **MIT License**.

---

<div align="center">

## ⭐ If you find this project useful, don't forget to Star the repository ⭐

### 🚗 Predict Smarter. Drive Better. 🚀

</div>
