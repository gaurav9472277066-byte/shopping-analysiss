# Shopping Dataset Analysis

A beginner-friendly Python project that performs **data cleaning, exploratory data analysis (EDA), and feature engineering** on an e-commerce product dataset using **Pandas, Matplotlib, and Seaborn**.

---

## Project Structure

```
shopping-analysis/
├── data/
│   └── combined_dataset.csv       # Raw product data (1000 records)
├── notebook/
│   └── analysis.ipynb             # Jupyter Notebook with full analysis
├── output/
│   ├── cleaned_dataset.csv        # Cleaned data with engineered features
│   └── images/                    # Generated visualizations
│       ├── price_distribution.png
│       ├── top_brands.png
│       ├── rating_boxplot.png
│       ├── price_vs_rating.png
│       ├── brand_prices.png
│       └── correlation_heatmap.png
├── README.md
```

---

## What It Does

| Step | Description |
|------|-------------|
| **Load Data** | Read CSV into Pandas DataFrame |
| **Explore** | Check shape, columns, data types, missing values |
| **Clean** | Fix price formatting (₹, commas), handle missing values, remove duplicates |
| **Basic Ops** | Filter, select, sort, groupby |
| **Feature Engineering** | Price difference, discount %, quantity, total amount, popularity score |
| **Visualize** | Histograms, bar charts, boxplots, scatter plots, correlation heatmap |
| **Export** | Save cleaned dataset with all new features |

---

## Requirements

- Python 3.7+
- pandas
- numpy
- matplotlib
- seaborn

Install with:
```bash
pip install pandas numpy matplotlib seaborn
```

---

## How to Run

```bash
jupyter notebook notebook/analysis.ipynb
```

Or open it directly in VS Code / Google Colab.

---

## Key Findings

- Prices vary widely — from budget-friendly to premium across categories
- Most products are rated between 3.5–4.5 stars
- Some brands dominate in product count and customer engagement
- Popularity metric helps identify top-performing products beyond just ratings

---

*Assignment project for Python & Data Science coursework.*
