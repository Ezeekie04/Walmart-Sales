# Walmart-Sales-Analysis

## Contents

### 1. Data Files

- **`initial_dataset.csv`**: The raw dataset from Kaggle, containing features such as store, fuel price, CPI, and unemployment.
- **`predictions.csv`**: Contains columns for `Actual`, `Predicted`, and `Error` values, used for evaluating the Random Forest model.
- **`trend_analysis.csv`**: Preprocessed data for trend analysis of actual vs predicted sales over time.
- **`feature_importance.csv`**: Feature importance scores computed from the Random Forest model.
- **`aggregated_sales.csv`**: Aggregated sales data by store.

### 2. Notebook

- **`portfolio 3.ipynb`**: Contains the complete workflow, including:
  - Data preprocessing
  - Feature engineering
  - Model training (Random Forest Regressor)
  - Error analysis and evaluation
  - Exporting data for visualization

### 3. Visualization

All visualizations were created in Tableau using the exported CSV files. Dashboards include:
- Actual vs Predicted Sales
- Trend Analysis Over Time
- Feature Importance
- Error Distribution
- Aggregated Sales by Store

## Getting Started

### Prerequisites

1. Install Python libraries:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```

2. Install Jupyter Notebook:
   ```bash
   pip install notebook
   ```

3. Install Tableau Public (free) to view or modify dashboards:
   [Download Tableau Public](https://public.tableau.com/)

### How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/retail-sales-analysis.git
   cd retail-sales-analysis
   ```

2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook notebooks/retail_sales_analysis.ipynb
   ```

3. Execute the cells sequentially to reproduce the analysis.

4. Open Tableau Public and load the CSV files in the `data` folder to reproduce the dashboards.

## Key Findings

1. **Prediction Performance**:
   - RMSE: `19431550820.64`
   - R² Score: `0.93`
2. **Sales Trends**:
   - Seasonal and temporal trends were observed.

## Acknowledgments

- Kaggle for providing the initial dataset.
- Tableau Public for enabling powerful data visualization.

