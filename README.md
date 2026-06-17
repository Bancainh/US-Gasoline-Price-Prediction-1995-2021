# U.S. Retail Gasoline Price Trend Prediction

## 📝 Project Overview
This project applies **Supervised Machine Learning** to predict the trend of retail gasoline prices in the United States. Instead of predicting specific continuous price values, the model classifies the price trend for the upcoming month as either **"Up"** or **"Down/Flat"**. This classification assists consumers and logistics companies in making informed fuel storage decisions and budget planning.

## 🚀 Tech Stack
* **Language:** Python
* **Libraries:** `pandas`, `numpy`, `scikit-learn`
* **Models:** Logistic Regression, Decision Tree Classifier

## 📊 Methodology
1. **Data Processing:** Cleaned and processed historical pricing datasets (1995–2021); performed feature engineering on the target variable (Up/Down) to identify seasonal market trends.
2. **Feature Selection:** Utilized key predictors: `Previous_Month_Gas_Price`, `Current_Diesel_Price`, and `Month` (to capture seasonal demand).
3. **Model Development:** Built and compared classification models (Logistic Regression vs. Decision Tree) to evaluate predictive performance.

## 📈 Key Findings & Evaluation
* **Performance:** The Decision Tree Classifier demonstrated better capability in capturing non-linear relationships compared to Logistic Regression.
* **Insights:** `Current_Diesel_Price` emerged as a strong predictor, and the `Month` feature highlighted increased travel demand during summer months.
* **Limitations:** The current model lacks macroeconomic variables (e.g., inflation, geopolitical crises) which are planned for future analysis.

## 🛠 Setup & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/Bancainh/US-Gasoline-Price-Prediction-1995-2021/tree/main
2. Install the required dependencies:
   pip install pandas numpy scikit-learn
3. Execute the analysis script:
   python main.py
