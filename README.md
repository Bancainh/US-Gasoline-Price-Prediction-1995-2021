# U.S. Retail Gasoline Price Trend Prediction

## 📝 Project Overview
This project applies **Supervised Machine Learning** to predict the trend of retail gasoline prices in the United States. Instead of predicting specific continuous price values, the model classifies the price trend for the upcoming month as either **"Up"** or **"Down/Flat"**. [cite_start]This classification assists consumers and logistics companies in making informed fuel storage decisions and budget planning[cite: 2, 3, 4].

## 🚀 Tech Stack
* **Language:** Python
* **Libraries:** `pandas`, `numpy`, `scikit-learn`
* **Models:** Logistic Regression, Decision Tree Classifier

## 📊 Methodology
1. [cite_start]**Data Processing:** Cleaned and processed historical pricing datasets (1995–2021); performed feature engineering on the target variable (Up/Down) to identify seasonal market trends[cite: 5, 6, 7].
2. [cite_start]**Feature Selection:** Utilized key predictors: `Previous_Month_Gas_Price`, `Current_Diesel_Price`, and `Month` (to capture seasonal demand)[cite: 8, 10, 11].
3. [cite_start]**Model Development:** Built and compared classification models (Logistic Regression vs. Decision Tree) to evaluate predictive performance[cite: 13, 16].

## 📈 Key Findings & Evaluation
* [cite_start]**Performance:** The Decision Tree Classifier demonstrated better capability in capturing non-linear relationships compared to Logistic Regression[cite: 15, 17].
* [cite_start]**Insights:** `Current_Diesel_Price` emerged as a strong predictor, and the `Month` feature highlighted increased travel demand during summer months[cite: 20, 21].
* [cite_start]**Limitations:** The current model lacks macroeconomic variables (e.g., inflation, geopolitical crises) which are planned for future analysis[cite: 24, 25, 27].

## 🛠 Setup & Usage
1. Clone the repository:
   ```bash
   git clone <your-repository-url>
2. Install the required dependencies:
   pip install pandas numpy scikit-learn
3. Execute the analysis script:
   python main.py
