# FoodDelivery-Analysis 🚀

**A reproducible AI-driven framework integrating ChatGPT with the Technology Acceptance Model (TAM) to analyze 1.6M food delivery app reviews.**

---

## 🔹 Key Features

- Merge raw app review datasets from **DoorDash**, **Grubhub**, and **Uber Eats**.
- Perform sentiment analysis using **Afinn** and **VADER**.
- Extract TAM constructs: **Ease of Use**, **Usefulness**, **Intention to Use**.
- Conduct correlation and regression analysis to study adoption behavior.
- Generate visualizations and word clouds for strategic insights.

---

## 📂 Repository Structure


FoodDelivery-Analysis/
├── notebooks/ # Jupyter notebooks for processing and analysis
│ ├── 01_merge_dataset.ipynb
│ ├── 02_sentiment_analysis.ipynb
│ ├── 03_TAM_feature_engineering.ipynb
│ └── 04_analysis_and_results.ipynb
├── LICENSE
├── README.md
└── .gitignore


> ⚠️ Note: Large datasets are not included in this repository. See **Final Dataset** section below.

---

## ⚡ Quick Start

1. Install required Python packages:

```bash
pip install pandas afinn vaderSentiment matplotlib wordcloud statsmodels

Run notebooks in order:

01_merge_dataset.ipynb → 02_sentiment_analysis.ipynb → 03_TAM_feature_engineering.ipynb → 04_analysis_and_results.ipynb
📜 License

This project is licensed under the MIT License. See LICENSE for details.


### Final Dataset

The final processed dataset (`fooddelivery_updated_sentiment2.csv`, 1.52 GB) is available on Mendeley:

[Download from Mendeley Data](https://data.mendeley.com/datasets/m5jk7wzyg7/1)
