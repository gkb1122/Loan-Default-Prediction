Loan Default Prediction Model
This machine learning model predicts whether a borrower will default on their loan, helping lenders assess risk and make informed decisions. Built with LightGBM and SVM, it processes loan application data, handles class imbalance, and provides interpretable predictions.

Key Features
✅ Data Preprocessing – Handles missing values, encodes categorical features, and scales numerical data for optimal model performance.

✅ Class Balancing – Uses SMOTE (Synthetic Minority Oversampling Technique) to address dataset imbalance, ensuring fair prediction of defaults.

✅ Model Training & Evaluation – Implements LightGBM (Gradient Boosting) and SVM (Support Vector Machine), with performance metrics including:

Classification Report (Precision, Recall, F1-Score)

Confusion Matrix (Visualized with Seaborn)

ROC Curve & AUC Score (Measures model discrimination ability)

✅ Prediction Deployment – Generates a CSV output with risk scores for new loan applications.

Business Value
📉 Risk Mitigation – Flags high-risk borrowers before approval, reducing financial losses.

📊 Data-Driven Decisions – Provides probabilistic risk scores instead of binary approvals/rejections.

🔄 Continuous Improvement – Recommends periodic model retraining with new data for better accuracy.

Usage
Upload your training and test datasets (CSV format).

Preprocessing automatically handles missing data and feature engineering.

Model Training runs LightGBM and SVM, with evaluation metrics displayed.

Predictions are exported to loan_default_predictions.csv.

Recommendations for Lenders
🔍 Focus on High-Risk Features – Income, loan amount, and credit history heavily influence predictions.

⚖️ Adjust Approval Thresholds – Use probability scores to align with your institution's risk appetite.

📢 Explainable AI – Visualize feature importance (SHAP/LIME) to justify decisions to stakeholders.

Getting Started
Install dependencies:

pip install lightgbm scikit-learn imbalanced-learn pandas matplotlib seaborn

Run the script and upload your dataset when prompted.

License
MIT License – Free for commercial and academic use.
