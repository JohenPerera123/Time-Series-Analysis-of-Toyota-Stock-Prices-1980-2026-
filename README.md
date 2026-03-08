# 📈 Time Series Analysis and Forecasting of Toyota Stock Prices (1980–2026)

![Python](https://img.shields.io/badge/Python-3.9-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Statsmodels](https://img.shields.io/badge/Statsmodels-Time%20Series-orange)
![Status](https://img.shields.io/badge/Project-Completed-success)
![License](https://img.shields.io/badge/License-MIT-red)

---

## 📊 Project Overview

This project performs a comprehensive **Time Series Analysis of Toyota Motor Corporation stock prices** using historical financial data from **1980 to 2026**.

The main goal of this study is to analyze stock price behavior and develop **forecasting models** using classical statistical methods.

The project implements and compares several models including:

- 🔹 **Autoregressive Model (AR)**
- 🔹 **Moving Average Model (MA)**
- 🔹 **Autoregressive Integrated Moving Average (ARIMA)**

The performance of these models is evaluated using multiple **statistical error metrics** to determine the most accurate forecasting method.

---

## 📁 Dataset

The dataset contains historical **Toyota stock price data** including:

| Column | Description |
|------|-------------|
| 📅 Date | Trading date |
| 📈 Open | Opening stock price |
| 🔼 High | Highest price of the day |
| 🔽 Low | Lowest price of the day |
| 💰 Close | Closing stock price |
| 🔢 Volume | Number of shares traded |

The **Closing Price** variable is mainly used for the time series analysis.

---

## 🛠 Technologies Used

This project is implemented using the following tools and libraries:

- 🐍 **Python**
- 📊 **Pandas**
- 🔢 **NumPy**
- 📉 **Matplotlib**
- 🎨 **Seaborn**
- 📚 **Statsmodels**
- 🤖 **Scikit-learn**
- 📓 **Jupyter Notebook / Google Colab**

---

## ⚙️ Project Workflow

The project follows a structured **Time Series Analysis pipeline**:

### 1️⃣ Data Preprocessing
- Load dataset
- Handle missing values
- Convert date formats

### 2️⃣ Exploratory Data Analysis
- Time series visualization
- Trend analysis
- Data distribution analysis

### 3️⃣ Seasonal Pattern Analysis
- 📅 Monthly variation
- 📆 Weekly patterns

### 4️⃣ Stationarity Testing
- Rolling statistics
- Differencing transformation

### 5️⃣ Time Series Modeling

The following forecasting models are implemented:

- 📌 **Autoregressive Model (AR)**
- 📌 **Moving Average Model (MA)**
- 📌 **ARIMA Model**

### 6️⃣ Model Evaluation
Model performance is evaluated using several statistical metrics.

---

## 📏 Model Evaluation Metrics

### 🔹 Mean Absolute Error (MAE)

```
MAE = (1/n) Σ |y_t - ŷ_t|
```

Measures the **average magnitude of prediction errors**.

---

### 🔹 Mean Squared Error (MSE)

```
MSE = (1/n) Σ (y_t - ŷ_t)²
```

Penalizes **larger prediction errors more strongly**.

---

### 🔹 Root Mean Squared Error (RMSE)

```
RMSE = √MSE
```

Represents prediction error **in the same units as the data**.

---

### 🔹 Mean Absolute Percentage Error (MAPE)

```
MAPE = (100/n) Σ |(y_t - ŷ_t) / y_t|
```

Measures prediction error as a **percentage**.

---

## 🧠 Model Performance Comparison

| Model | MAD | MAE | MSE | RMSE | MAPE (%) |
|------|------|------|------|------|------|
| 📈 AR(1) | 0.0579 | 0.0579 | 0.00795 | 0.08918 | **1.95** |
| 📉 MA(5) | 3.3854 | 3.3854 | 16.1815 | 4.0226 | 119.72 |
| 📊 ARIMA(1,2,2) | 90.9571 | 90.9571 | 15679.97 | 125.22 | 3150.51 |
| 📊 ARIMA(1,1,2) | 2.1130 | 2.1130 | 4.7531 | 2.1802 | 75.22 |

🏆 **Result:**  
The **AR(1) model provides the lowest prediction error**, making it the best forecasting model for this dataset.

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git
```

---

### 2️⃣ Navigate to the Project Directory

```bash
cd YOUR_REPOSITORY_NAME
```

---

### 3️⃣ Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn statsmodels scikit-learn
```

---

### 4️⃣ Run the Notebook

Open the notebook file:

```
Time_Series_Analysis_of_Toyota_Stock_Prices.ipynb
```

You can run it using:

- 📓 Jupyter Notebook
- ☁️ Google Colab
- 🧪 Jupyter Lab

---

## 📂 Project Structure

```
Toyota-Stock-Time-Series-Analysis
│
├── 📓 Time_Series_Analysis_of_Toyota_Stock_Prices.ipynb
├── 📁 dataset
│   └── toyota_stock_prices.csv
├── 📄 README.md
```

---

## 🔍 Key Findings

✅ Toyota stock prices show a **long-term upward trend**  
✅ The time series initially shows **non-stationary behavior**  
✅ Differencing stabilizes the series  
✅ **AR(1) provides the most accurate predictions**

---

## 🔮 Future Work

Future improvements may include:

- 📊 **SARIMA models**
- 📉 **GARCH volatility modeling**
- 🤖 **Machine Learning models (LSTM, RNN)**
- 🌍 Incorporating **economic indicators**

---

## 👨‍💻 Author

**Johen Perera**

🔗 GitHub Profile  
https://github.com/JohenPerera123

---

⭐ If you like this project, feel free to **star the repository**!
