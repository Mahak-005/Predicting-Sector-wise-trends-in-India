# **📊 Predicting Sector-wise Labor Productivity Trends in India**


#### **🧠 Overview**
This capstone project explores sector-wise labor productivity trends in India using historical data ranging from 1960 to 2018. The goal was to:

- **Analyze productivity across sectors such as agriculture, manufacturing, trade, and finance.**

- **Predict future trends using regression models.**

- **Forecast labor productivity using time-series models like ARIMA and SARIMA.**

Labor productivity is a key economic indicator and understanding its patterns is critical for policy planning, business strategy, and research.

---

#### **📁 Dataset**
1. **Source: World Bank Data**

2. **Features:**

- **Sector: Economic sectors (Agriculture, Mining, Manufacturing, etc.)**

- **Year: 1960–2018**

- **Value Added (Nominal & Real): Output measures with and without inflation adjustment**

- **Employment: Sector-wise employment numbers**

- **Labor Productivity (Real & PPP): Output per worker with inflation and PPP adjustments**

  ---

#### **🧹 Data Preprocessing**

1. **Converted data types for consistency.**

2. **Checked and confirmed absence of missing values.**

3. **Handled outliers to maintain data integrity.**

4. **Encoded categorical sector labels into numerical format.**

5. **Generated a correlation heatmap for variable relationships.**

   ---

#### **🔍 Exploratory Data Analysis (EDA)**

- **Histograms and box plots for each numeric variable.**

- **Sector-wise bar plots for visualizing distribution.**

- **Scatter plots to analyze variable relationships.**

- **Performed ADF Test to check stationarity of time-series data.**

  ---

#### **🧪 Modeling & Predictions**

🔹 Linear Regression
**Achieved near-perfect prediction with:**

- **RMSE ≈ 2.53e-11**

- **R² score = 1.0**

🔹 Random Forest Classifier

- **Accuracy: 93% on test set**

- **Provided strong classification performance**

🔹 PCA (Principal Component Analysis)
**Used for dimensionality reduction before model training**

---

####**📈 Time Series Forecasting**

🔸 ARIMA
-**Performed well with good fit and low error metrics**

-**Residuals were normally distributed and independent**

🔸 SARIMA
- **Captured trends and seasonality**

- **But resulted in high MSE: 493,919,156,840,630.1**

- **Indicating limited forecasting accuracy for this model**

  ---

#### **💡 Key Insights**

- **Linear regression yielded excellent predictive performance, indicating strong relationships between productivity and input features.**

- **Random forest performed well as a classifier, supporting its robustness for structured data.**

- **Time-series models showed ARIMA to be more effective than SARIMA for this dataset.**

- **Sector-wise productivity trends varied significantly, underlining the importance of sector-specific policies.**

  ---

#### **📌 Technologies Used**

- **Python**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **scikit-learn**
- **statsmodels (ARIMA/SARIMA)**
