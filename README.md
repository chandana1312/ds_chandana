# Trader Behavior vs Market Sentiment Analysis

This project analyzes the relationship between trader behavior and market sentiment (Fear vs Greed) using real trading data from Hyperliquid and sentiment data from the Bitcoin Fear & Greed Index.

---

## 🔗 Important Links

- 📔 Google Colab Notebook: [Open notebook_1.ipynb](https://colab.research.google.com/drive/1UV9B7UiX6HvRn7DqV-x7SOBJNDhnYCoO?usp=sharing)
- 📁 GitHub Repository: [ds_chandana](https://github.com/chandana1312/ds_chandana)

---

## 📂 Folder Structure

```
ds_chandana/
├── notebook_1.ipynb
├── csv_files/
│   ├── merged_data.csv
│   └── daily_summary.csv
├── outputs/
│   ├── avg_pnl_by_sentiment.png
│   ├── volume_by_sentiment.png
│   └── exec_price_trend.png
├── ds_report.pdf
└── README.md
```


## 📊 Overview

- **Datasets Used**:
  - 🔹 [Bitcoin Fear & Greed Index](https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing)
  - 🔹 [Hyperliquid Trader Data](https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing)

- **Main Objective**:
  Analyze how trading behavior (PnL, leverage, volume) aligns or diverges from market sentiment patterns.

---

## 📌 Insights

- Traders tend to take **larger risks during Greed** phases.
- **PnL tends to drop** during extreme sentiment transitions (fear → greed).
- Hidden behavior patterns were detected via date-wise aggregations.

---

## ⚙️ Requirements

- Google Colab (no local setup needed)
- Python 3.11+
- Libraries: `pandas`, `matplotlib`, `seaborn`

---

## 📬 Submission Format

This repository follows the required structure for the assignment as mentioned by the Web3 Trading Team.

---

