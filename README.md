# 🧠 Sales Forecasting with Linear Regression

This project uses historical sales data to forecast future sales using regression techniques in Python. It's designed for business teams who need data-driven insights into upcoming sales trends.

## 📊 Problem Statement

Businesses struggle to estimate future sales based on past performance. This project builds a predictive model to forecast upcoming sales using Linear Regression.

## 📁 Dataset

- Sales data includes: `Date`, `Product`, `Quantity Sold`, `Revenue`
- You can replace with your own CSV file (`sales_data.csv`)

## ⚙️ Tools & Libraries

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- gspread (for Google Sheets integration)

## 🧮 Workflow

1. Load and clean the dataset
2. Preprocess data: handle dates, fill missing values
3. Create and train a Linear Regression model
4. Visualize actual vs predicted sales
5. Export results (optionally to Google Sheets)

## 📈 Output Example

- Line chart: Actual vs Predicted Sales
- Summary statistics
- Forecasted sales table

## ▶️ Run It

Install dependencies:
```bash
pip install -r requirements.txt
```

Open the notebook:
```bash
jupyter notebook polished_sales_forecasting_project.ipynb
```

## 📄 License

[MIT License](LICENSE)
