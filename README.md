### 🛡️ Fraud Detection Using PaySim Dataset

## 📌 Overview
This project tackles the challenge of detecting fraudulent transactions using the PaySim synthetic dataset. It combines rigorous data preprocessing, feature engineering, and machine learning modeling to build a robust fraud detection pipeline. Beyond the code, this project reflects a personal journey of persistence, learning, and growth in the field of data science.

## 💪 Personal Journey
“This wasn’t just a project—it was a test of my patience, curiosity, and determination.”

As a student at LNCT University, I embarked on this project with limited resources and no formal mentorship. I faced:

Data imbalance that distorted model performance

Noisy features that confused classifiers

Model instability across thresholds

But through trial, error, and relentless debugging, I built a reproducible pipeline that not only detects fraud but also explains why a transaction is flagged—because interpretability matters.

## 🧠 What I Learned
Advanced feature engineering: mismatch flags, transaction type encoding, and time-based features

Model tuning: comparing XGBoost variants with scale_pos_weight vs SMOTE

Threshold optimization: precision-recall tradeoffs for real-world deployment

Visualization: Seaborn and Matplotlib plots to interpret fraud patterns

Version control: GitHub workflows and documentation for reproducibility

## 📊 Project Highlights
✅ Cleaned and transformed 6M+ transaction records

✅ Built  ML models (XGBoost)

✅ Achieved Recall ≥ 90% while maximizing Precision

✅ Created threshold tuning logic to meet business KPIs

✅ Documented every phase for clarity and reproducibility

## 🧰 Tech Stack
Python (Pandas, NumPy, Seaborn, Matplotlib)

Scikit-learn, XGBoost

Jupyter Notebook

Git & GitHub

## 📁 File Structure
Code
fraud_detection/
├── Fruad_detection.ipynb  # Main notebook with full pipeline
├── README.md              # Project overview and personal story
## 🚀 Future Enhancements
Deploy model via Streamlit for interactive fraud flagging
## 🙌 Acknowledgments
To every bug that tested my patience, and every late night that taught me something new—this project is a tribute to the journey of becoming a data scientist.

Integrate real-time API simulation for transaction scoring

🙌 Acknowledgments
To every bug that tested my patience, and every late night that taught me something new—this project is a tribute to the journey of becoming a data scientist.
