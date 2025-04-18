💳 Fraud Detection System using XGBoost
This project focuses on building a machine learning model to detect fraudulent transactions using the XGBoost algorithm. The goal is to accurately classify transactions as fraudulent or not, using a combination of preprocessing, oversampling, and model evaluation techniques.

📊 Dataset
The dataset includes transaction-level information.
The target column is isFraud (1 for fraudulent, 0 for legitimate).
Features include time, amount, sender/receiver info, and more.

⚙️ Technologies Used
Python
Pandas, NumPy – Data manipulation
Scikit-learn – Preprocessing, evaluation
XGBoost – Main ML model
Matplotlib, Seaborn – Visualization

Model Details
Model: XGBoost Classifier

Strategy:
Random Oversampling to handle class imbalance
StratifiedKFold Cross-Validation to ensure balanced evaluation
Metrics used: Accuracy, Precision, Recall, F1-score, ROC-AUC

 Future Improvements
Implement real-time fraud detection using streaming data
Try other ML algorithms like LightGBM, CatBoost
Tune hyperparameters for improved performance
Add a web dashboard for visualization
 
Author
Shreeya Sati
shreeyasati@gmail.com

