## Telecom Customer Churn Analysis & Prediction AI (ML)
This project uses a real-world telecom dataset to build a machine learning model that **predicts customer churn** and **reveals the top reasons behind it**. Businesses can use this model to **retain valuable customers** and **reduce revenue loss** 💰

## 🎯 Business Problem
Telecom companies lose millions due to customer churn. By predicting **who is likely to leave** and understanding **why**, we can take proactive actions to:
- 🛑 Prevent churn  
- 🤝 Improve customer satisfaction  
- 📈 Maximize long-term revenue

## 🧠 3️⃣ Tools & Skills Used
✅ SQL (Exploratory Data Analysis, Business Insights)  
✅ Python (Pandas, Scikit-Learn, Matplotlib, Seaborn)  
✅ AI/ML (Random Forest Classifier for churn prediction)  
✅ Data Visualization & Feature Importance  
✅ Google Colab for implementation

## 💡 4️⃣ What I Did 
📌 Used SQL to explore customer churn patterns:
    • Identified churn trends based on contract type, tenure, and payment method
    • Grouped customers as new, mid, or long-term based on their tenure
    • Found top regions with high churn using aggregate queries
📌 Loaded CSV dataset into Google Colab and cleaned it using pandas
📌 Built an ML Model using Random Forest Classifier to predict if a customer will churn
📌 Analyzed the most important features affecting churn using feature importance charts
📌 Achieved high model performance and created business-ready insights

## ✅ Step-by-Step Simple Breakdown
🔹Step 1: Load the Data
🔹Step 2: Clean the Data
      🧠 This means: Some values in "TotalCharges" were not numbers (like empty strings). So we told Python:
      👉 “Convert everything to numbers. If it fails, mark it as missing (NaN).”
   Then we told it:
      👉 “Fill those missing values using the middle value (median) of the column.”
🔹 Step 3: Convert Text to Numbers.
🔹 Step 4: Convert Categorical Columns
            ➡ Text values like “Payment Method = Credit Card” are turned into 1s and 0s. 
                  This is needed because machine learning works with numbers, not text.

🔹 Step 5: Split into Training & Testing
            X = Features like tenure, charges, contract, etc.
            y = What we want to predict: whether they stayed, churned, or joined
            We split data: 80% for training, 20% for testing
🔹 Step 6: Train the Model
            🧠 This builds the model. It learns patterns from the training data.
🔹 Step 7: Check How Well Model Works
![https://github.com/Sapna3950/-Churn-Analysis-Prediction-Using-AI-ML-](Predict new customers.png)

✅ It predicted “Stayed” correctly 939 times!
✅ But sometimes made mistakes predicting "Joined" as "Churned", etc.

## Overall: Accuracy is 97% — that’s awesome!
Precision and F1-score also look high. This means it’s doing a great job.
🔹 Step 8: Predict New Customers
![https://github.com/Sapna3950/-Churn-Analysis-Prediction-Using-AI-ML-](https://github.com/Sapna3950/-Churn-Analysis-Prediction-Using-AI-ML-/blob/main/Predict%20new%20customers)
🧠 Meaning:
1st, 2nd, 3rd, and 5th customers will Stay (0)
4th customer is predicted to be Joined (2)

🔹 Step 9: Feature Importance
🧠 This tells you: “These features matter the most when the model decides whether someone churns or not.”

For example:
1. If customer left because of a competitor, the model gives that high weight
2. Longer tenure usually means they will stay
3. Total revenue/charges help indicate their value and history

## 💥 5️⃣ Outcome
✅ Built an AI-powered churn predictor with ~80%+ accuracy  
✅ Delivered data-driven recommendations to reduce customer loss  
✅ Demonstrated end-to-end workflow: SQL → Python → ML → Insights


---

Let me know when you're ready to jump into the **AI chatbot for churn prevention** – this one’s gonna be really fun and impressive! 🤖💬


