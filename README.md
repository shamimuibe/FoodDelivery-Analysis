# FoodDelivery-Analysis 🚀

**A reproducible AI-driven framework integrating ChatGPT with the Technology Acceptance Model (TAM) to analyze 1.6M food delivery app reviews.**

---

## 🔹 Key Features

- Merge raw app review datasets from DoorDash, Grubhub, and Uber Eats.
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
├── data/ # Raw and processed datasets
│ ├── DoorDash.csv
│ ├── Grubhub.csv
│ ├── Uber_Eats.csv
│ ├── fooddelivery_updated.csv
│ ├── fooddelivery_updated_sentiment.csv
│ └── fooddelivery_updated_sentiment2.csv # Final dataset
├── LICENSE
├── README.md
└── .gitignore


---

## ⚡ Quick Start

1. Install required Python packages:

```bash
pip install pandas afinn vaderSentiment matplotlib wordcloud statsmodels

Run notebooks in order:

01_merge_dataset.ipynb → 02_sentiment_analysis.ipynb → 03_TAM_feature_engineering.ipynb → 04_analysis_and_results.ipynb
📜 License

This project is licensed under the MIT License. See LICENSE for details.


✅ **Advantages of this version:**

- Quick overview for visitors  
- Emojis for visual appeal  
- Clear “Quick Start” section  
- Highlights TAM + AI integration as the main innovation  

If you want, I can also **write a very short “abstract-style” blurb** to add right at the top so it looks like a mini-paper summary. This is often helpful for research repos.  

Do you want me to do that too?
