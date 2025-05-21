# 🏦 Bank Marketing Campaign - Term Deposit Prediction

A Machine Learning project to predict whether a customer will subscribe to a term deposit based on marketing call data. Built as part of DS675 at NJIT.

## 📁 Project Structure

📦Bank Campaign Response System/
├── final.ipynb
├── train.csv
├── test.csv
├── public/
│ ├── correlation_matrix.png
│ ├── target_distribution.png
│ └── feature_distributions.png


## 🧠 Objective

To use historical marketing data from a Portuguese bank to predict customer responses and improve the efficiency of future campaigns. Only ~11% of previous campaigns were successful — highlighting the need for better targeting using machine learning.

## 🧪 Dataset

- **Source:** UCI Machine Learning Repository  
- **Size:** 45,211 entries  
- **Features:** 16 input features + 1 binary target

### Features Include:
- Client demographics: `age`, `job`, `marital`, `education`
- Financial data: `balance`, `loan`, `housing`
- Call data: `duration`, `day`, `month`, `campaign`, `pdays`, `previous`

## 📊 EDA Highlights

- **Class Imbalance:** Majority class is “No” (~88%)
- **Correlations:** Low correlation among most features, but `duration` and `previous` are moderately correlated
- Visuals available in `public/` folder

## ⚙️ Models Used

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
- AUC-ROC for model discrimination
- SHAP values for model interpretability (future work)

## 🚀 Future Work

- Use of SMOTE for class imbalance
- Deploying with Streamlit or Flask
- SHAP/PFI for feature importance analysis

## 👨‍💻 Authors

- Nikhil Yarra  
- Vishnu Sunil  
- Ahmeduddin Yasar Mohammed  
- Saitej Deep Kumar Chowdary Bodapati

## 📸 Visualizations

Stored in `public/` folder:
- `correlation_matrix.png`
- `target_distribution.png`
- `feature_distributions.png`

---

Feel free to fork or contribute!

