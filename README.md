# 📊 Customer Lifetime Value (CLTV) Prediction Project

## 🧩 Introduction
This project predicts the Customer Lifetime Value (CLTV) of customers using the **Online Retail II** dataset. The goal is to identify high-value customers and assist targeted marketing and retention strategies.

---

## 🎯 Objective
- Predict the lifetime value (LTV) of customers based on purchase history.
- Segment customers based on predicted CLTV for better decision-making.

---

## 🛠️ Tools and Technologies
- **Python** (Pandas, Lifetimes, Matplotlib)
- **Google Colab / Jupyter Notebook**
- **Excel** (for final report/output)
- **Dataset**: [Online Retail II - UCI Repository](https://archive.ics.uci.edu/ml/datasets/Online+Retail+II)

---

## 🧠 Steps Involved

1. **Data Collection & Cleaning**:
   - Imported Online Retail II dataset.
   - Removed missing customer IDs and canceled invoices.

2. **Feature Engineering**:
   - Calculated TotalPrice = Quantity × Price.
   - Aggregated data into Recency, Frequency, and Monetary Value.

3. **Model Training**:
   - Trained **BG/NBD model** for frequency prediction.
   - Trained **Gamma-Gamma model** for monetary prediction.

4. **CLTV Calculation**:
   - Combined BG/NBD and Gamma-Gamma outputs to compute CLTV.

5. **Customer Segmentation**:
   - Segmented customers into groups A, B, C, and D based on CLTV quartiles.

6. **Output and Export**:
   - Saved final results in `cltv_predictions.xlsx`.
   - Visualized CLTV distribution using a histogram.

---

## 📦 Deliverables
- Python Notebook (`CLTV_Prediction.ipynb`)
- Excel File (`cltv_predictions.xlsx`)
- Project Report (`CLTV Project Report.pdf`)
- Visualizations (CLTV Distribution Plot)

---

## 🏁 Conclusion
The CLTV model successfully predicts customer value, helping businesses to focus on the most profitable segments. Future work may involve integrating the model into CRM systems for real-time predictions.

---
