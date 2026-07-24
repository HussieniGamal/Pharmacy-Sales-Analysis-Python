# Pharmacy Sales Analysis with Python

![Repository Cover](images/repository-cover.png)

A portfolio-ready exploratory data analysis project examining pharmaceutical sales across **daily, weekly, monthly, and hourly datasets**. The project uses Python to clean data, engineer time-based features, compare drug-category performance, identify seasonality, and translate analytical findings into practical business insights.

## Project Highlights

- **2,106 daily records** covering **2014-01-02 to 2019-10-08**
- **50,532 hourly records**
- **8 pharmaceutical categories**
- Time-series analysis at daily, weekly, monthly, annual, weekday, and hourly levels
- Reproducible Jupyter Notebook with documented analytical steps
- Cleaned dataset and high-resolution charts included

## Key Findings

| Finding | Result |
|---|---|
| Leading category | **N02BE** — Paracetamol / Analgesics |
| Share of total sales | **49.4%** |
| Strongest year | **2016** |
| Peak month | **January** |
| Lowest-demand month | **July** |
| Strongest weekday | **Saturday** |
| Peak hour | **19:00** |

## Business Questions Answered

1. Which pharmaceutical categories generate the highest sales?
2. How did total sales change across the available years?
3. Which months show the strongest and weakest demand?
4. Are there clear weekday or hourly purchasing patterns?
5. Which categories exhibit distinct seasonal behavior?
6. How can daily performance be classified into low, medium, and high bands?
7. Which drug categories move together?

## Tools and Skills

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Data cleaning and validation
- Feature engineering
- Exploratory data analysis
- Time-series aggregation
- Correlation analysis
- Data storytelling

## Repository Structure

```text
Pharmacy-Sales-Analysis-Python/
├── data/
│   ├── salesdaily.csv
│   ├── salesdaily_cleaned.csv
│   ├── salesweekly.csv
│   ├── salesmonthly.csv
│   └── saleshourly.csv
├── images/
│   ├── repository-cover.png
│   ├── 01_total_sales_by_category.png
│   ├── 02_annual_sales_trend.png
│   ├── 03_monthly_seasonality.png
│   ├── 04_weekday_sales_profile.png
│   ├── 05_hourly_sales_pattern.png
│   ├── 06_monthly_category_patterns.png
│   ├── 07_performance_bands.png
│   └── 08_category_correlation_matrix.png
├── notebook/
│   └── pharmacy_sales_analysis.ipynb
├── DATA_DICTIONARY.md
├── requirements.txt
├── .gitignore
└── README.md
```

## Selected Visualizations

### Category Performance

![Category Performance](images/01_total_sales_by_category.png)

### Annual Sales Trend

![Annual Trend](images/02_annual_sales_trend.png)

### Monthly Seasonality

![Monthly Seasonality](images/03_monthly_seasonality.png)

### Hourly Demand Pattern

![Hourly Pattern](images/05_hourly_sales_pattern.png)

### Drug Category Seasonality

![Category Seasonality](images/06_monthly_category_patterns.png)

### Category Correlation

![Correlation Matrix](images/08_category_correlation_matrix.png)

## Analysis Workflow

1. Loaded and inspected four time-granularity datasets.
2. Validated data types, missing values, and analytical fields.
3. Converted date fields and derived year, month, quarter, and weekday attributes.
4. Calculated total sales across eight pharmaceutical categories.
5. Built category contribution, annual trend, monthly seasonality, weekday, and hourly analyses.
6. Classified daily sales into performance bands using the 33rd and 66th percentiles.
7. Examined correlations between pharmaceutical categories.
8. Exported a cleaned dataset for reuse.

## Run Locally

```bash
git clone https://github.com/HussieniGamal/Pharmacy-Sales-Analysis-Python.git
cd Pharmacy-Sales-Analysis-Python
pip install -r requirements.txt
jupyter notebook notebook/pharmacy_sales_analysis.ipynb
```

## Dataset

The raw files correspond to the public **Pharma Sales Data** dataset. Drug categories follow ATC classification codes.

## Author

**Hussieni Gamal**  
Data Analyst | Power BI | SQL | Excel | Python

- GitHub: https://github.com/HussieniGamal
- LinkedIn: https://www.linkedin.com/in/hussieni-gamal-549b68134
