# 🏦 Bank Marketing Campaign - Term Deposit Prediction

A Machine Learning project that predicts whether a customer will subscribe to a term deposit, based on previous marketing campaign data. Developed for DS675 at NJIT.

## 📁 Project Structure

📦 Bank Campaign Response System/
├── final.ipynb
├── train.csv
├── test.csv
├── public/
│ ├── correlation_matrix.png
│ ├── target_distribution.png
│ └── feature_distributions.png

## 🧠 Objective

To optimize direct marketing campaigns by identifying clients likely to subscribe to term deposits using machine learning models and predictive analytics.

## 📊 Dataset

- **Source:** UCI Machine Learning Repository  
- **Instances:** 45,211 clients  
- **Features:** 16 (client demographics, campaign info, call logs)  
- **Target:** Binary (Subscribed: Yes/No)

## 🧪 Exploratory Data Analysis

- Strong class imbalance (88% NO vs 12% YES)
- Moderate correlation between `duration`, `previous` and target
- Visuals are stored in the `public/` folder

## 🤖 Models Used

- Logistic Regression
- SVM
- Random Forest
- XGBoost
- Neural Network

### 📈 Best Performing Model

**Random Forest**
- Accuracy: 98%  
- Precision: 95%  
- Recall: 89%  
- F1 Score: 92%  

## 🧮 Evaluation Metrics

- Accuracy, Precision, Recall, F1 Score  
- AUC-ROC  
- SHAP (planned for future analysis)

## 🚀 Future Work

- Handle class imbalance using SMOTE
- Deploy model via Streamlit or Flask
- Visualize model explanations using SHAP

## 👨‍💻 Author

- Nikhil Yarra  

## 📸 Visualizations

Found in `public/`:
- `correlation_matrix.png`
- `target_distribution.png`
- `feature_distributions.png`

---

Built with ❤️ using Python, Scikit-Learn, and Jupyter.

