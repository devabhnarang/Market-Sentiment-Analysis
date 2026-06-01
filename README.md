# Hyperliquid Trader Performance vs Market Sentiment Analysis

## Project Overview

This project analyzes the relationship between Bitcoin market sentiment and trader behavior on Hyperliquid using the Fear & Greed Index and historical trading data.

The goal of the analysis was to understand how different market sentiment conditions influence:

* trader profitability
* trading activity
* trade sizes
* behavioral patterns

The project also explores trader segmentation and clustering to identify different trading archetypes and extract actionable trading insights.

---

# Setup & Run Instructions

## 1. Clone the Repository

```bash
git clone https://github.com/devabhnarang/Market-Sentiment-Analysis
cd market-sentiment-analysis
```

---

## 2. Install Required Libraries

Make sure Python is installed on your system.

Install all dependencies using:

```bash
pip install -r requirements.txt
```

---

## 3. Extract Dataset Files

The datasets are included as ZIP files inside the `data/` folder.

Extract the ZIP files so the folder contains:

```text
data/
├── historical_data.csv
└── fear_greed_index.csv
```

---

## 4. Open Jupyter Notebook

Run:

```bash
jupyter notebook
```

Then open:

```text
analysis.ipynb
```

---

## 5. Run the Notebook

Run all notebook cells sequentially from top to bottom.

The notebook performs:

* data cleaning
* preprocessing
* dataset merging
* feature engineering
* trader behavior analysis
* Fear vs Greed comparison
* trader segmentation
* clustering analysis
* visualization generation

---

# Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

# Project Structure

```text
market-sentiment-analysis/
│
├── data/
│   ├── historical_data.zip
│   └── fear_greed_index.zip
│
├── charts/
├── analysis.ipynb
├── Project_Report.md
├── requirements.txt
└── README.md
```

---

# Notes

* Charts and visualizations are generated directly inside the notebook.
* The project focuses on understanding how market sentiment impacts trader behavior and performance on Hyperliquid.
* The clustering section was added as a bonus analysis to identify different trader behavior patterns.
