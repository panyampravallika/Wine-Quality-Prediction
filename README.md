# 🍷 Wine Quality Prediction using Machine Learning

This project aims to predict the quality of red wine using supervised machine learning algorithms based on its physicochemical features.

## 📌 Objective
To build a classification model that predicts wine quality (low, medium, or high) and supports wineries in making automated, data-driven quality decisions.

## 📊 Dataset
- **Name:** winequality-red.csv
- **Source:** UCI Machine Learning Repository  
- **Colab Notebook:** [View on Google Colab](https://colab.research.google.com/drive/1mp2qRGyha0J4RQz4xau200mRTOLuiht3?usp=sharing)
- **Local File:** Included in the repository (`winequality-red.csv`)
- **Features:**
  - Fixed Acidity, Volatile Acidity, Citric Acid
  - Residual Sugar, Chlorides, Free Sulfur Dioxide
  - Total Sulfur Dioxide, Density, pH, Sulphates, Alcohol
  - Output: `quality` (score between 0–10)

## 🛠️ Tools & Technologies
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Platform:** Google Colab

## ⚙️ Workflow
1. **Data Preprocessing**
   - Checked for missing values
   - Normalized feature values
   - Transformed quality scores into categories: low (3–4), medium (5–6), high (7+)

2. **Exploratory Data Analysis**
   - Correlation heatmaps
   - Box plots for feature comparison
   - Visualized distribution of quality categories

3. **Model Training**
   - Algorithms used: Logistic Regression, SVM, Random Forest, KNN
   - Best model: **Random Forest Classifier**

4. **Model Evaluation**
   - Metrics: Accuracy, Precision, Recall, F1-score
   - Final accuracy achieved: **93%**

## 📈 Result
The **Random Forest** model showed the best accuracy and generalization on test data. This model can be a robust tool for wine producers to assess product quality reliably.

## 🚀 Future Enhancements
- Deploy as a web app using Streamlit
- Try ensemble models like XGBoost or LightGBM
- Use multi-class classification without quality binning
