# 💳 Financial Fraud Detection Using Machine Learning  

## 📄 Description  
Built a machine learning pipeline to detect fraudulent financial transactions using a large real-world dataset.  
Includes:  
- **Jupyter Notebook (`analysis_model.ipynb`)** for training & analysis  
- **Streamlit web app (`fraud_detection.py`)** for real-time fraud prediction  
- **Trained ML pipeline (`fraud_detection_pipeline.pkl`)** for deployment  

---

## 📂 Dataset  
The full dataset is available on Kaggle:  
👉 [Financial Fraud Detection Dataset (Kaggle)](https://www.kaggle.com/datasets/sriharshaeedala/financial-fraud-detection-dataset)  

Due to size, the dataset is not uploaded here. Please download directly from Kaggle.  

---

## 🧩 Key Tasks  
- Cleaned & preprocessed 6M+ transaction records  
- Performed **Exploratory Data Analysis (EDA)** using Pandas, Matplotlib, Seaborn  
- Encoded categorical variables (transaction type)  
- Scaled numerical features with `StandardScaler`  
- Trained & evaluated multiple ML models (Logistic Regression, Random Forest, etc.)  
- Saved final pipeline with **Joblib**  
- Developed a **Streamlit app** for user-friendly fraud detection  

---

## 📊 Insights  
- Fraud is concentrated in **TRANSFER** and **CASH-OUT** transactions  
- Fraudsters often drain sender’s balance to zero in a single transaction  
- Rule-based system (`isFlaggedFraud`) misses many cases  
- Machine learning models improved fraud detection accuracy significantly  

---

## 🛠️ Tech Stack  
- **Python**  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Streamlit, Joblib  

---
## 👤 Author

Junaid Kamate

