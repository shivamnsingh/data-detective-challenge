# 🗓️ 30-Day Data Science Project Series
### One Problem. One Post. Every Day.

**Format:** Each day = a self-contained mini-project (90 min cap). Load data → 3 quick EDA charts → 1 baseline model → 1-sentence insight → LinkedIn post. No deployment, no deep tuning — the goal is consistency, not perfection.

---

## How to Run This Series

1. **Fix a 90-minute cap per project.** Load → clean → 3 EDA charts → 1 baseline model → 1 insight. That's it.
2. **Reuse one template notebook** (`load → clean → EDA → baseline model → insight → export chart`) so you're only swapping the dataset each day, not rebuilding structure.
3. **LinkedIn post formula (keep it consistent):**
   - Hook question (the clickbait title below)
   - 1 chart image
   - 2-line insight
   - "Tools: X, Y, Z"
   - Link to notebook/GitHub
4. **Batch-download all 30 datasets on Day 0** so you're never blocked mid-series.

---

## Day-by-Day Lineup

| Day | Hook (LinkedIn Title) | Dataset | Tech Stack (keep it fast) |
|---|---|---|---|
| 1 | "Can You Predict a Divorce From a Questionnaire Alone?" | [Divorce Predictors (UCI)](https://archive.ics.uci.edu/dataset/497/divorce+predictors+data+set) | pandas + sklearn LogisticRegression, 1 chart |
| 2 | "Someone Is Stealing Millions from Visa Every Hour" | [Credit Card Fraud](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) | pandas, SMOTE, XGBoost, 1 SHAP plot |
| 3 | "Amazon's ₹100 Crore Inventory Problem" | [Retail Demand Forecasting](https://www.kaggle.com/datasets/felixzhao/productdemandforecasting) | SQL groupby aggregation + simple moving avg forecast |
| 4 | "Why Did This Airline Lose ₹50 Crore Last Month?" | [Airline Delay & Cancellation](https://www.kaggle.com/datasets/threnjen/2019-airline-delays-and-cancellations) | pandas SQL-style joins + delay driver EDA |
| 5 | "Can You Catch an Insider Trader Before the Stock Market Does?" | [NYSE Price/Volume Data](https://www.kaggle.com/datasets/borismarjanovic/price-volume-data-for-all-us-stocks-etfs) | pandas rolling z-score anomaly detection |
| 6 | "Someone Is Creating Thousands of Fake Reviews on Amazon" | [Amazon Reviews (Fake/Real subset)](https://www.kaggle.com/datasets/lievgarcia/amazon-reviews) | TF-IDF + Naive Bayes, 1-day NLP |
| 7 | "The Starbucks Store That Always Runs Out of Coffee" | [Retail Demand Forecasting](https://www.kaggle.com/c/demand-forecasting-kernels-only) | pandas time series, rolling average |
| 8 | "Can You Predict Which Employee Will Quit Next?" | [IBM HR Analytics Attrition](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset) | pandas EDA + RandomForest + feature importance |
| 9 | "Uber Has 50,000 Drivers... Where Should They Go Next?" | [Uber Pickups NYC](https://www.kaggle.com/datasets/fivethirtyeight/uber-pickups-in-new-york-city) | pandas heatmap + geospatial clustering (KMeans/DBSCAN) |
| 10 | "Netflix Is Losing Subscribers Every Day — Can You Stop It?" | [Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) | pandas + LogisticRegression, quick and clean |
| 11 | "The ₹500 Crore Loan Default Mystery" | [Lending Club Loan Data](https://www.kaggle.com/datasets/wordsforthewise/lending-club) | pandas SQL-style filtering + XGBoost |
| 12 | "Can AI Catch Cancer Before the Doctor Does?" | [Breast Cancer Wisconsin](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data) | SVM/LogReg + precision-recall curve |
| 13 | "The Recommendation Engine That Could've Saved Blockbuster" | [MovieLens](https://grouplens.org/datasets/movielens/) | cosine similarity, no deep learning needed |
| 14 | "Why Is This Online Store Losing ₹2 Crore to Abandoned Carts?" | [E-commerce Data (UK Retailer)](https://www.kaggle.com/datasets/carrie1/ecommerce-data) | pandas funnel analysis + classification |
| 15 | "Spot the Deepfake Before It Goes Viral" | [Deepfake Detection Challenge](https://www.kaggle.com/c/deepfake-detection-challenge) | transfer learning on a small CNN, scoped to a handful of clips |
| 16 | "The Hospital That Keeps Readmitting the Same Patients" | [Diabetes 130-US Hospitals](https://archive.ics.uci.edu/dataset/296/diabetes+130-us+hospitals+for+years+1999-2008) | pandas + LogisticRegression, class imbalance note |
| 17 | "The Traffic Signal Costing a City ₹10 Crore a Year" | [Traffic Prediction Dataset](https://www.kaggle.com/datasets/hasibullahaman/traffic-prediction-dataset) | pandas + simple ARIMA, keep it light |
| 18 | "Can You Predict Money Laundering in Real Time?" | [PaySim Mobile Money](https://www.kaggle.com/datasets/ealaxi/paysim1) | pandas + IsolationForest, one anomaly technique |
| 19 | "Predicting a Wine's Quality Using Nothing But Chemistry" | [Wine Quality (UCI)](https://archive.ics.uci.edu/dataset/186/wine+quality) | sklearn classification, quick GridSearch |
| 20 | "The Hidden Bias Behind Loan Approvals" | [German Credit Data](https://archive.ics.uci.edu/dataset/144/statlog+german+credit+data) | fairness check: compare approval rates by group |
| 21 | "Predicting Customer Lifetime Value Before They've Bought Twice" | [Online Retail II](https://archive.ics.uci.edu/dataset/502/online+retail+ii) | SQL RFM query + regression |
| 22 | "The Crop That Fails Every Monsoon" | [Crop Yield Prediction](https://www.kaggle.com/datasets/patelris/crop-yield-prediction-dataset) | pandas regression + correlation heatmap |
| 23 | "Can You Predict a Startup's Success Before Investors Do?" | [Startup Success Prediction](https://www.kaggle.com/datasets/manishkc06/startup-success-prediction) | sklearn classification + feature importance |
| 24 | "The Spotify Skip Button Problem" | [Spotify Sequential Skip Prediction](https://www.aicrowd.com/challenges/spotify-sequential-skip-prediction-challenge) | scoped-down session model, simple RNN or logistic baseline |
| 25 | "Can You Catch an Edit War Before Wikipedia Locks the Page?" | [Wikipedia Talk Labels: Personal Attacks](https://meta.wikimedia.org/wiki/Research:Detox) | TF-IDF + classification on comment text |
| 26 | "Reddit's Court of Public Opinion: Predicting the Ahole" | [AITA Dataset](https://www.kaggle.com/datasets/hoyahong0530/reddit-aita-dataset) | TF-IDF + LogisticRegression baseline only |
| 27 | "The F1 Pit Stop That Cost a Championship" | [Ergast F1 Dataset](https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020) | SQL joins across race/pitstop tables + viz |
| 28 | "The Coffee Bean That Fooled the Experts" | [Coffee Quality Institute](https://github.com/jldbc/coffee-quality-database) | pandas regression, scatter plots |
| 29 | "Can a Model Tell Real UFO Sightings From Fakes?" | [NUFORC UFO Sightings](https://www.kaggle.com/datasets/NUFORC/ufo-sightings) | pandas NLP keyword tagging + geospatial plot |
| 30 | "Can You Predict a Marathon Runner's Meltdown Mile?" | [Boston Marathon Results](https://www.kaggle.com/datasets/rojour/boston-results) | pandas pacing analysis, regression |

---

## LinkedIn Post Template (copy-paste each day)

```
🚨 [HOOK QUESTION FROM TABLE]

[1-2 line setup of the business problem]

[Chart image]

Key insight: [1-2 line takeaway from your baseline model]

Tools: [pandas / sklearn / SQL / whatever you used today]

Notebook: [GitHub link]

#DataScience #MachineLearning #30DayChallenge
```

---

## Day 0 Checklist (do this before Day 1)

- [ ] Download all 30 datasets into `/data/day01` … `/data/day30`
- [ ] Build one reusable template notebook: `load → clean → EDA (3 charts) → baseline model → insight → export`
- [ ] Set up a public GitHub repo with a folder per day
- [ ] Draft your Day 1 LinkedIn post using the template above
