# Project Presentation: Time Series Forecasting Of Gold Price and Analysis.

---

## **1. Introduction**
Gold prices have shown a significant trend over the decades, driven by various economic, geopolitical, and market factors. This project explores gold price data from 1950 onwards, with the primary goal of understanding historical patterns and making future predictions. By leveraging statistical analysis and machine learning techniques, this project aims to provide insights into gold price trends and their variations over time.

---

## **2. Objectives**
- **Data Exploration**: To examine gold price trends over monthly, yearly, quarterly, and decadal timeframes.
- **Data Visualization**: To use visualizations for better understanding and communication of historical gold price trends.
- **Pattern Recognition**: To identify patterns and seasonality in gold prices.
- **Forecasting**: To predict future gold prices using both regression models and advanced time series forecasting techniques.
- **Error Measurement**: To evaluate the accuracy of forecasting models using metrics like MAPE (Mean Absolute Percentage Error).

---

## **3. Data Description**
- **Dataset**: The dataset includes monthly gold price data from 1950 to 2020.
- **Features**: The primary feature analyzed is the gold price over time.
- **Time Frame**: Data spans 70 years, providing a robust base for historical analysis and forecasting.

---

## **4. What I Did**
1. **Data Preprocessing**:
   - Loaded and cleaned the dataset.
   - Converted dates into a time-series format for efficient analysis.
   - Resampled the data into yearly, quarterly, and decadal averages.

2. **Exploratory Data Analysis (EDA)**:
   - Created boxplots to understand the distribution of prices over months and years.
   - Used line plots to visualize trends and fluctuations in gold prices over time.

3. **Descriptive Statistics**:
   - Calculated mean, standard deviation, and coefficient of variation to understand price volatility.

4. **Time Series Analysis**:
   - Used monthly, quarterly, and yearly aggregations to observe patterns and trends.
   - Performed seasonal decomposition to explore the additive components of trend and seasonality.

5. **Model Building and Forecasting**:
   - Applied **Linear Regression** on the training data to establish a baseline model for trend prediction.
   - Implemented **Exponential Smoothing** with additive trend and seasonality to enhance predictions.

6. **Model Evaluation**:
   - Calculated MAPE for both models to assess prediction accuracy.
   - Compared predicted values against actual test data.

7. **Visualization**:
   - Used matplotlib and seaborn for detailed trend and boxplot visualizations.
   - Plotted forecasts with confidence intervals to depict the reliability of the model.

---

## **5. Key Results**
- **Historical Trends**:
  - Observed a consistent upward trend in gold prices with periodic spikes.
  - High variability in prices across decades, driven by external market forces.

- **Seasonality Insights**:
  - Certain months showed higher average gold prices, indicating seasonal demand.

- **Forecasting Accuracy**:
  - Linear Regression yielded a MAPE of approximately *X%* on the test dataset.
  - Exponential Smoothing provided more accurate forecasts, with a MAPE of approximately *Y%*.

---

## **6. Conclusion**
This project successfully analyzed and forecasted gold price trends using a combination of statistical and machine learning models. By understanding historical patterns and making reliable predictions, such analyses can assist investors, policymakers, and economists in making informed decisions.

---

## **7. Future Scope**
- Integrate external factors such as inflation, stock market trends, and geopolitical events for multivariate forecasting.
- Use advanced techniques like ARIMA, Prophet, or LSTM for better long-term predictions.
- Expand the analysis to include real-time gold price data for continuous updates.

---

## **8. Tools and Libraries Used**
- **Python Libraries**: pandas, numpy, matplotlib, seaborn, statsmodels, scikit-learn.
- **Visualization**: Detailed plots for trends, seasonality, and predictions.
- **Modeling Techniques**: Linear Regression, Exponential Smoothing.

