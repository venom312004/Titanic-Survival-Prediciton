# 🚢 Titanic Survival Prediction

This project predicts whether a passenger survived the Titanic disaster using multiple machine learning models. The focus is on comparing model performance using key classification metrics.

---

## 📌 Problem Statement

Predict passenger survival:
- **0 → Did Not Survive**
- **1 → Survived**

Based on features like age, gender, ticket class, fare, etc.

---

## 📂 Dataset

- Dataset: Titanic Dataset  
- Target Variable: `Survived`

### 🧩 Features:
- Age  
- Sex  
- Passenger Class (Pclass)  
- Fare  
- Embarked  
- SibSp (siblings/spouses aboard)  
- Parch (parents/children aboard)  

---

## ⚙️ Workflow

1. Data Loading  
2. Data Cleaning  
   - Handling missing values  
   - Dropping unnecessary columns  
3. Feature Engineering  
   - Encoding categorical variables  
4. Train-Test Split  
5. Model Training  
6. Model Evaluation  

---

## 🤖 Models Used

- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Naive Bayes  
- Decision Tree  
- Support Vector Machine (SVM)  

---

## 📊 Evaluation Metrics

- **Accuracy** → Overall correctness of the model  
- **Precision** → Out of predicted survivors, how many were correct  
- **Recall** → Out of actual survivors, how many were correctly predicted  
- **F1 Score** → Balance between precision and recall  

---

## 📈 Results

- Logistic Regression performed as a strong baseline model.  
- Decision Tree and SVM showed competitive performance.  
- Precision and recall revealed trade-offs between false positives and false negatives.  
- No single model dominates — performance depends on the metric priority.


---
## 🧠 Key Insights

- Gender and passenger class are strong indicators of survival.  
- Data preprocessing significantly impacts model performance.  
- Simpler models can perform well on structured datasets.  

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/your-username/titanic-survival-prediction.git

# Navigate to project folder
cd titanic-survival-prediction

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook
```
---
## 📌 Conclusion

This project demonstrates that machine learning models can effectively predict survival outcomes using structured data, even with relatively simple techniques.

Among all models tested, Logistic Regression provided a strong and reliable baseline, while more complex models like Decision Tree and SVM offered competitive performance depending on the evaluation metric. This highlights an important reality: **model selection should be driven by the problem objective, not just accuracy**.

A key takeaway is the trade-off between precision and recall. In real-world scenarios, choosing the right balance is critical—for example, whether it is more important to minimize false positives or false negatives.

Additionally, the project reinforces that:
- Data preprocessing and feature engineering have a significant impact on performance  
- Simpler models can generalize well on structured datasets  
- Understanding model behavior is as important as achieving high accuracy  

Overall, this project builds a strong foundation in classification, evaluation metrics, and practical machine learning workflows, while also highlighting areas for improvement such as model tuning, validation, and deployment.
