# Bitcoin_Market_Sentiment_Dataset
Bitcoin_Market_Sentiment_Dataset PreProcessing
Bitcoin Market Sentiment & Trader Performance Analysis
Project Overview
This project analyzes the relationship between Bitcoin market sentiment (Fear, Greed, etc.) and trader performance using two datasets:

Bitcoin Market Sentiment Dataset (daily sentiment classifications)

Historical Trader Data from Hyperliquid (trade details, profits, fees, etc.)

The goal is to uncover patterns linking market sentiment with trader profitability and behavior.

Repository Structure
bash
Copy
Edit
ds_<your_name>/
├── notebook_1.ipynb         # Main analysis notebook (Google Colab)
├── csv_files/               # Raw and processed CSV files
├── outputs/                 # Visual outputs: charts and graphs (PNG/JPG)
├── ds_report.pdf            # Final project report with insights
└── README.md                # This file
How to Use
Open notebook_1.ipynb in Google Colab to explore the code and analysis step-by-step.

See the outputs/ folder for all charts and visual results.

Read ds_report.pdf for a summary of insights and conclusions.

Tools & Libraries Used
Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)

Google Colab for interactive coding and visualization

Notes
Missing data was handled by dropping or imputing where necessary.

Categorical data was encoded for analysis.

Statistical tests confirmed significant effects of market sentiment on trader profits.


