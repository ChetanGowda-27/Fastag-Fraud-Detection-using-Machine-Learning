# Fastag Fraud Detection using Machine Learning

🚗 **Detecting Fraudulent Fastag Transactions with Machine Learning** 💳

Welcome to the Fastag Fraud Detection project! This repository showcases how machine learning can be leveraged to detect fraudulent transactions in the Fastag system. The project covers **data exploration**, **feature engineering**, **visualization**, and prepares the dataset for **fraud prediction**.

---

## 🛠️ **Technologies Used**
- **Python**  
- **Pandas** (Data manipulation)
- **Seaborn / Matplotlib** (Visualization)
- **Scikit-learn** (Machine learning)
  
---

## 📊 **Key Features**
- **Data Exploration**: Dive deep into vehicle types, toll booths, and transaction amounts.
- **Feature Engineering**: Handle missing data, extract state codes from vehicle numbers, and analyze time-based features.
- **Visualization**: Visualize fraudulent transactions based on different features like vehicle types, toll booths, and time.
- **Fraud Prediction**: Build machine learning models to predict fraudulent transactions.

---

## 🚗 **Dataset Overview**
The dataset contains multiple features such as:
- **Vehicle Type**
- **Toll Booth ID**
- **Transaction Amount**
- **Vehicle Speed**
- **Timestamp**
- **Fraud Indicator** (Target variable)

---

## 🔍 **How it Works**
1. **Data Cleaning & Exploration**: Clean the data by handling missing values, duplicates, and statistical analysis.
2. **Feature Engineering**: Create new features such as `state_code` from the vehicle plate number.
3. **Data Visualization**: Use graphs and charts to identify patterns related to fraudulent activity.
4. **Machine Learning**: Train models to classify whether a transaction is fraudulent based on the extracted features.

---

## 📈 **Visualizations**
- **Fraud distribution across states, vehicle types, and toll booths.**
- **Transaction amount vs. paid amount (scatter plot).**
- **Hour of day, day of the week, and month analysis for fraud activity.**

---

## 💡 **Getting Started**

To run the project on your local machine:

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Fastag-Fraud-Detection.git
   ```
   
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the script to explore the data and train the model.

---

## 📬 **Contact**
If you have any questions or suggestions, feel free to open an issue or contact me directly!

---

### Let's stop fraud, one Fastag at a time! 🔐

