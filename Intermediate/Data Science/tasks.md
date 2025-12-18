# Data Science Tasks - Intermediate Level

Complete **ANY TWO** of the following tasks.

---

## Task 1: End-to-End ML Pipeline

### Objective
Build a complete machine learning pipeline from data to deployment-ready model.

### Requirements
1. Choose a real-world dataset (Kaggle or UCI)
2. Implement complete pipeline:
   - Data loading and validation
   - Exploratory data analysis
   - Data cleaning and preprocessing
   - Feature engineering
   - Model training and validation
   - Model evaluation and comparison
3. Handle:
   - Missing values
   - Outliers
   - Categorical variables
   - Data imbalance (if present)
4. Try at least 3 different models
5. Implement cross-validation
6. Create model performance report
7. Save final model for deployment

### Hints
- Use sklearn pipelines
- Implement proper train/validation/test splits
- Document all decisions
- Consider computational efficiency

---

## Task 2: Time Series Forecasting

### Objective
Build models to forecast future values in time series data.

### Requirements
1. Obtain or create time series data
2. Perform time series analysis:
   - Trend analysis
   - Seasonality detection
   - Stationarity tests
3. Implement forecasting methods:
   - Moving averages
   - ARIMA or SARIMA
   - Prophet or similar
   - ML-based approach (if applicable)
4. Handle:
   - Missing timestamps
   - Outliers
   - Seasonal patterns
5. Evaluate with appropriate metrics (MAE, RMSE, MAPE)
6. Create forecast visualizations
7. Provide prediction intervals

### Hints
- Use statsmodels or prophet
- Split data chronologically
- Validate on multiple periods
- Consider external factors/features

---

## Task 3: Customer Churn Prediction

### Objective
Build a system to predict customer churn and identify key factors.

### Requirements
1. Use or create customer dataset with churn labels
2. Conduct exploratory analysis:
   - Churn rate and patterns
   - Feature distributions by churn status
   - Correlation analysis
3. Engineer relevant features:
   - Usage patterns
   - Engagement metrics
   - Tenure-based features
4. Build prediction models:
   - Try multiple algorithms
   - Handle class imbalance
   - Optimize for business metric
5. Interpret model:
   - Feature importance
   - SHAP values or similar
6. Provide actionable recommendations
7. Create customer risk scores

### Hints
- Use appropriate evaluation metrics (F1, precision-recall)
- Consider cost of false positives vs false negatives
- Focus on interpretability
- Think about business applications

---

## Evaluation Criteria

- **Correctness**: Pipeline works end-to-end
- **Code Quality**: Professional, maintainable code
- **Performance**: Good model results
- **Analysis**: Deep insights and interpretations
- **Business Value**: Actionable recommendations
