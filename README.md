## Credit Card Fraud Detection

The Credit Card Fraud Detection system is built using a **supervised machine learning classification model** trained to distinguish between **fraudulent** and **legitimate** credit card transactions.

The trained model and preprocessing scaler are loaded using **Joblib** to ensure consistency between training and real-time prediction.

### Model Details:
- **Problem Type:** Binary Classification
- **Target Variable:** `Class`
  - `0` → Legitimate Transaction
  - `1` → Fraudulent Transaction
- **Saved Model File:** `fraud_model.pkl`
- **Feature Scaler:** `scaler.pkl`
- **Prediction Outputs:**
  - `Predicted_Class` (0 or 1)
  - `Fraud_Probability` (confidence score)

### Prediction Workflow:
- User uploads a transaction dataset in CSV format
- Input features are scaled using the trained scaler
- Model predicts fraud class and probability for each transaction
- If actual labels are present, performance metrics are displayed

### Model Evaluation Metrics:
- Precision
- Recall
- F1-Score
- Support  
(Evaluated using **Classification Report** when true labels are available)



## 🔮 Future Enhancements

The Credit Card Fraud Detection system can be enhanced with the following improvements:

- Integrate advanced algorithms such as **XGBoost, LightGBM, or Deep Learning**
- Implement **real-time transaction streaming** using APIs or Kafka
- Add **anomaly detection** for previously unseen fraud patterns
- Store detected fraud cases in a secure database
- Implement **Explainable AI (SHAP / LIME)** for model transparency
- Add role-based authentication for bank officials
- Deploy the application on **AWS, Azure, or Streamlit Cloud**
- Enable alerts via email or SMS for high-risk transactions



## 📜 Conclusion

This Credit Card Fraud Detection project demonstrates an effective **end-to-end machine learning solution** for identifying fraudulent transactions in real time. The system integrates **pre-trained ML models, feature scaling, probability-based predictions, and interactive Streamlit visualizations**.

The application highlights how machine learning can be applied in **financial security and risk management**, making it an ideal project for **final-year academics, fintech portfolios, and real-world fraud detection scenarios**.

## 📬 Feel Free to Contact
If you have any questions, suggestions, or would like to collaborate, feel free to reach out:

- **Name:** Sneha pranathi Guddinti
- **Email:** snehapranathi21@gmail.com  
- **LinkedIn:** https://www.linkedin.com/in/sneha-pranathi-guddinti-3176a029b/  
- **GitHub:** https://github.com/snehapranathi21 

I am always open to feedback, learning opportunities, and collaboration.
