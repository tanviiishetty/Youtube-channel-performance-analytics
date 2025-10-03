# 📊 YouTube Channel Performance Analysis & Revenue Prediction  

## 📌 Overview  
This project analyzes YouTube channel performance metrics and builds a **machine learning model** to predict revenue. It covers the full pipeline from **EDA → Feature Engineering → Modeling → Model Export**.  

---

## ⚙️ Tech Stack  
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Joblib  

---
## 🔍 Workflow  

1. **Data Exploration (EDA)**  
   - Summary statistics  
   - Correlation heatmaps  
   - Visualization of key metrics  

2. **Feature Engineering**  
   - `Revenue per View = Estimated Revenue / Views`  
   - `Engagement Rate = (Likes + Shares + New Comments) / Views × 100`  

3. **Modeling**  
   - Random Forest Regressor  
   - Train/test split  
   - Evaluation with **MSE** and **R²**  

4. **Model Export**  
   - Saved using `joblib.dump()` as `youtube_revenue_predictor.pkl`  

---

## 📈 Results  
- **Engagement metrics** (likes, shares, comments) have strong influence on revenue.  
- The Random Forest model provides reasonable revenue predictions.  
- Insights can guide **content strategy & monetization** decisions.  

---

## 🚀 How to Run  

```bash
# Clone repo
git clone https://github.com/yourusername/YouTube_Performance_Analysis.git

# Install dependencies
pip install -r requirements.txt

# Run notebook
jupyter notebook notebooks/EDA_and_Modeling.ipynb
