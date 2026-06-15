# 🥇 Gold Price Prediction using Machine Learning

A Machine Learning project that predicts Gold (GLD) prices using historical market data and a Random Forest Regressor. The project involves data preprocessing, correlation analysis, visualization, model training, and performance evaluation.

## 📌 Project Overview

Gold prices are influenced by several economic and financial factors. This project uses historical market indicators to build a regression model capable of predicting gold prices with high accuracy.

The workflow includes:

- Data Collection and Preprocessing
- Exploratory Data Analysis (EDA)
- Correlation Analysis
- Feature Selection
- Model Training using Random Forest Regressor
- Model Evaluation
- Actual vs Predicted Price Comparison

---

## 🎯 Objective

To predict the price of gold (GLD) using related financial indicators and machine learning techniques.

---

## 📊 Dataset Information

The dataset contains historical gold price data along with other market-related features.

### Features Used

| Feature | Description |
|----------|-------------|
| SPX | S&P 500 Index |
| USO | United States Oil Fund Price |
| SLV | Silver Price |
| EUR/USD | Euro to US Dollar Exchange Rate |
| GLD | Gold Price (Target Variable) |

---

## 🔍 Exploratory Data Analysis

Performed the following analyses:

- Dataset inspection and statistical summary
- Missing value detection
- Correlation matrix generation
- Heatmap visualization
- Gold price distribution analysis

### Key Insights

- No missing values were found in the dataset.
- Strong relationships exist between gold prices and certain financial indicators.
- Correlation analysis helped identify the most influential features for prediction.

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🤖 Machine Learning Model

### Algorithm

- Random Forest Regressor

### Why Random Forest?

- Handles non-linear relationships effectively
- Reduces overfitting through ensemble learning
- Provides robust performance on real-world datasets

### Training Configuration

- Train-Test Split: 80:20
- Random State: 2
- Number of Trees: 100

---

## 📈 Model Evaluation

The model performance was evaluated using:

### Evaluation Metric

- **R² Score (Coefficient of Determination)**

A higher R² score indicates better prediction accuracy and model performance.

---

## 📉 Visualization

The project compares:

- Actual Gold Prices
- Predicted Gold Prices

using a line plot to visually assess model performance.

---

## 📂 Project Structure

```text
Gold-Price-Prediction/
│
├── Gold_Price_Prediction.ipynb
├── gld_price_data.csv
├── README.md
└── requirements.txt
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/gold-price-prediction.git
```

Move into the project directory:

```bash
cd gold-price-prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
Gold_Price_Prediction.ipynb
```

Run all cells sequentially.

---

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Data preprocessing
- Exploratory Data Analysis (EDA)
- Correlation analysis
- Feature engineering
- Regression modeling
- Random Forest algorithms
- Model evaluation using R² Score
- Data visualization

---

## 🔮 Future Improvements

- Hyperparameter tuning using GridSearchCV
- XGBoost Regressor implementation
- Model deployment using Streamlit
- Real-time gold price forecasting
- Feature importance analysis

---

## 👨‍💻 Author

**Akhil Kraleti**

Computer Science Undergraduate | Data Science & Machine Learning Enthusiast

---

⭐ If you found this project useful, consider giving it a star!
