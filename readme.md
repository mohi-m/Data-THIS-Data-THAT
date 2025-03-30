# Customer Spend Analysis and Risk Management Project

This project focuses on analyzing customer spending behavior, predicting future spending trends, classifying customer accounts, identifying high-risk accounts, and suggesting credit line adjustments. The analysis is performed using historical transaction data and involves building various machine learning models to support decision-making.

---

## 📂 Project Structure

The project is divided into four key components, each represented by a Jupyter notebook:

### 1. *Spend Analysis and Forecasting*
•⁠  ⁠*Notebook:* ⁠ spend_analysis_forecast.ipynb ⁠
•⁠  ⁠The goal was to analyze customer spending behavior and predict future spending for *Q4 2025*.
•⁠  ⁠The *Prophet Model* was implemented to capture trends, seasonality, and anomalies in the data.
•⁠  ⁠Forecasted spending values for *October, November, and December 2025* were generated.

---

### 2. *Customer Segmentation*
•⁠  ⁠*Notebook:* ⁠ classification_model_customer_segmentation.ipynb ⁠
•⁠  ⁠A *Random Forest Classifier* was built to segment customer accounts into categories based on their financial behavior.
•⁠  ⁠Accounts were classified as: 
  - *Eligible for Credit Line Increase without Risk*
  - *Eligible for Credit Line Increase with Risk*
  - *Non-Performing Account*
  - *No Credit Line Increase Required*
•⁠  ⁠This helps in making data-driven decisions on credit management.

---

### 3. *Risk Identification*
•⁠  ⁠*Notebook:* ⁠ Risk_Identification_Model.ipynb ⁠
•⁠  ⁠An *Isolation Forest* model was used for anomaly detection to identify high-risk accounts.
•⁠  ⁠The model flagged potentially fraudulent or default-prone accounts based on transaction and account activity data.
•⁠  ⁠This supports early intervention and fraud prevention measures.

---

### 4. *Credit Line Adjustment*
•⁠  ⁠*Notebook:* ⁠ credit_line_adjustment_model.ipynb ⁠
•⁠  ⁠A *Regression-based Model* was developed to suggest appropriate credit line adjustments for individual accounts.
•⁠  ⁠Factors such as past spending behavior, payment history, and risk scores were considered.
•⁠  ⁠The model predicts the optimal credit line increase while minimizing the risk of default.

---

## 🛠️ Tools and Libraries Used

•⁠  ⁠*Python*
•⁠  ⁠*Pandas*
•⁠  ⁠*NumPy*
•⁠  ⁠*Matplotlib*
•⁠  ⁠*Seaborn*
•⁠  ⁠*Scikit-Learn*
•⁠  ⁠*Prophet* (for time series forecasting)
•⁠  ⁠*Statsmodels*

---

## 🚀 How to Run the Project

1.⁠ ⁠*Clone the repository* using Git:
    ⁠ bash
    git clone <repository_link>
     ⁠
2.⁠ ⁠*Ensure Python and Jupyter Notebook* are installed.
3.⁠ ⁠*Install dependencies* using:
    ⁠ bash
    pip install -r requirements.txt
     ⁠
4.⁠ ⁠*Run the notebooks* in the following order:
    - ⁠ spend_analysis_forecast.ipynb ⁠
    - ⁠ classification_model_customer_segmentation.ipynb ⁠
    - ⁠ Risk_Identification_Model.ipynb ⁠
    - ⁠ credit_line_adjustment_model.ipynb ⁠

---

## 📊 Conclusion

This project provides actionable insights into customer behavior through spend analysis and forecasting, customer segmentation, risk identification, and credit line adjustment recommendations. The developed models support financial institutions in making informed decisions regarding credit management, fraud detection, and risk mitigation.

For any questions or further information, please reach out to the project contributors.