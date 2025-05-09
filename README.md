# 🏃 Athlete Injury Risk Prediction using AI/ML

This project aims to predict injury risks in collegiate athletes using supervised machine learning techniques. By analyzing physical, training, and physiological data, our model identifies athletes who are likely to sustain injuries, helping coaches and staff make data-driven decisions to enhance safety and performance.

## 📌 Objective
- Predict the likelihood of athlete injuries using machine learning.
- Analyze key metrics like training intensity, fatigue, ACL risk score, and heartbeat.
- Provide actionable insights for injury prevention.

## 📊 Dataset
- `collegiate_athlete_data.xlsx`  
- 17 features including age, gender, training hours, fatigue score, ACL risk score, and more.
- Target: `Injury_Indicator` (1 = Injury, 0 = No Injury)

## 🔍 Methodology
- Preprocessing: Encoding, feature scaling, handling missing values.
- Algorithms Used:
  - Logistic Regression
  - Support Vector Machine (SVM)
  - XGBoost Classifier
  - ✅ **Random Forest Classifier** (Best Accuracy: 70%)

## 📈 Key Findings (EDA)
- Overtraining (15+ hrs/week), high fatigue, and elevated heartbeat linked to injuries.
- Strong correlation between ACL risk, fatigue, and injury occurrence.
- Gender-based analysis showed slightly varied injury patterns.

## 📌 Evaluation Metrics
- Accuracy, Precision, Recall, F1-Score, Confusion Matrix, ROC-AUC.
- **Random Forest** had the best balance of accuracy and recall, making it ideal for deployment.

## ✅ Final Output
- A trained ML model capable of early injury prediction.
- Visualizations for key insights (bar graphs, heatmaps, scatter and box plots).
- Feature importance rankings for interpretability.

## 📚 Conclusion
ML models—especially ensemble ones like Random Forest—can significantly aid in reducing preventable injuries by identifying at-risk athletes early. This project demonstrates how data-driven sports science can optimize training and enhance athlete longevity.

## 🚀 How to Use
1. Clone this repo:  
   `git clone https://github.com/your-username/athlete-injury-prediction.git`
2. Install dependencies:  
   `pip install -r requirements.txt`
3. Run the model script or notebook to train and test predictions.

## 📎 Authors
- Jayant Singh (102303226)
- Gursharen Kaur Suri (102303227)
- Prabhjot Singh (102303234)

> Submitted as part of Artificial Intelligence (UCS411) course project.
