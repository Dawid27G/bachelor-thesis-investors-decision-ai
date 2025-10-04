# 🎓 Predicting Individual Investors’ Decisions Using Artificial Intelligence

This repository contains the implementation of my **Bachelor’s thesis project** titled  
**“The Use of Artificial Intelligence for Predicting the Behavior of Individual Investors.”**  
The project explores how **machine learning** and **sentiment analysis** can be applied to predict investment decisions (Buy / Sell / Hold) of individual investors using **publicly available data**.

---

## 🧩 Project Overview

The goal of this study was to assess whether **artificial intelligence** can simulate investor behavior on the capital market.  
The research used a dataset for **Tesla Inc.**, combining:
- Traditional **market and technical indicators**
- **Media sentiment** extracted from financial news using the **FinBERT** NLP model  

Three types of investment strategies were simulated:
- 🔴 **Aggressive**
- 🟠 **Moderate**
- 🟢 **Conservative**

The **XGBoost** machine learning algorithm was applied to predict investor actions across forecast horizons of 10, 20, and 30 days.

---

## 📊 Key Results

- **Highest accuracy:** 88% for conservative, long-term (30-day) strategy  
- **Moderate strategy:** F1-score between 0.73 – 0.83  
- **Aggressive short-term:** F1-score ≈ 0.67  
- Longer horizons and balanced decision profiles → higher behavioral predictability  

---

## 🧰 Technologies Used

| Category | Tools |
|-----------|-------|
| Programming Language | Python |
| Machine Learning | XGBoost, Scikit-learn |
| NLP / Sentiment Analysis | FinBERT |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Environment | Jupyter Notebook |

---

## 🚀 How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Dawid27G/bachelor-thesis-investors-decision-ai.git
   cd bachelor-thesis-investors-decision-ai
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the notebook or script:**
   ```bash
   jupyter notebook investor_ai.ipynb
   ```
   or
   ```bash
   python main.py
   ```

---

## 🧠 Project Structure

```
📂 bachelor-thesis-investors-decision-ai
 ├── 📜 README.md
 ├── 📄 main.py / investor_ai.ipynb
 ├── 📁 data/           # Input datasets (market + sentiment)
 ├── 📁 models/         # Saved XGBoost models
 ├── 📁 plots/          # Visualizations and charts
 └── 📄 requirements.txt
```

---

## 🧮 Methodology

- Data collection: Tesla Inc. market indicators, technical metrics, and media sentiment
- Sentiment extraction: FinBERT (financial-domain BERT model)
- Labeling: Buy / Sell / Hold decisions assigned based on future returns
- Prediction model: XGBoost classifier trained and evaluated with Accuracy & F1 metrics
- Evaluation: Comparison across 10-, 20-, and 30-day forecast horizons

---

## 🧾 Conclusions

Artificial intelligence can **moderately predict the behavior of retail investors** based on publicly available data.  
Performance improves with:
- Longer forecast horizons  
- More conservative or balanced investor profiles  

This study highlights the potential of **AI and NLP** for behavioral finance applications, even when using only publicly available data.

---

## 🧑‍💻 Author

**Dawid Genert**  
Bachelor of Economic Analytics – Financial Analyst specialization  
Gdansk University of Technology
Supervisor: **dr hab. Oleksandr Melnychenko**

**Grade:** 5.0 (Excellent)

---

## 🔗 Links

- 📄 Thesis: *The Use of Artificial Intelligence for Predicting the Behavior of Individual Investors*  
- 💬 LinkedIn: [https://linkedin.com/in/dawidgenert](https://www.linkedin.com/in/dawid-genert-849374366) 
- 🤖 FinBERT Model: [https://github.com/ProsusAI/finBERT](https://github.com/ProsusAI/finBERT)

---

## 🏷️ Keywords
`Artificial Intelligence` · `Machine Learning` · `FinBERT` · `XGBoost` · `Sentiment Analysis` · `Investor Behavior` · `Behavioral Finance`
