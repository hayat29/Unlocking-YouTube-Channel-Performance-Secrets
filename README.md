

# 🔍 Unlocking YouTube Channel Performance Secrets

Welcome to your data-driven deep dive into the world of YouTube channel analytics! This project leverages real-world metrics to uncover what drives revenue, views, and engagement—and builds a predictive model to forecast a channel's success. Whether you're a data enthusiast, content creator, or aspiring analyst, this project is your launchpad.

---

## 📁 Project Overview

This end-to-end machine learning and data analysis pipeline:

- Cleans and preprocesses raw YouTube analytics
- Visualizes audience behavior, video effectiveness, and ad revenue
- Builds a predictive model to estimate revenue based on key variables
- Saves all results, plots, and the trained model for reuse

---

## 📊 Dataset Features

Your dataset captures rich information across:

- **Video Details:** duration, publish time, and day-of-week
- **Audience Metrics:** views, likes, shares, subscribers, and more
- **Revenue Stats:** ad impressions, CPM, and total estimated revenue
- **Engagement Signals:** click-through rates, watch time, and comments

---

## 🚀 Workflow Summary

1. **Import Libraries**  
2. **Data Loading & Preprocessing**  
3. **Feature Engineering (Revenue/View, Engagement Rate)**  
4. **Beautiful Visualizations (Histograms, Correlation Map, Scatterplots)**  
5. **Model Building (Random Forest Regressor)**  
6. **Model Evaluation (MSE, R² Score)**  
7. **Feature Importance Analysis**  
8. **Outputs Saved to `/outputs/`**

---

## 🖼️ Outputs

All visualizations and results are saved in the `outputs/` folder:

- `video_duration_distribution.png`  
- `revenue_distribution.png`  
- `revenue_vs_views.png`  
- `correlation_heatmap.png`  
- `feature_importance.png`  
- `model_metrics.txt`  
- `youtube_revenue_model.pkl`

---

## 🧠 Machine Learning Model

**Model Used:** Random Forest Regressor  
**Target Variable:** Estimated Revenue (USD)  
**Feature Inputs:** Views, Subscribers, Likes, Shares, Engagement Rate, etc.  
**Performance Metrics:** Written to `model_metrics.txt`

---

## 🛠️ Requirements

Install required Python libraries using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib
```

---

## 💡 Future Improvements

- Add Streamlit dashboard for interactivity  
- Tune hyperparameters to boost model performance  
- Extend analysis to forecast subscribers or engagement  
- Deploy model as an API or interactive web app

---

## 🙌 Author

Built with ❤️ by FAISAL – turning data into storytelling power.

