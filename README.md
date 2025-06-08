# 🧑‍💼 HR Analytics – Employee Attrition Prediction

Built and trained a machine learning model to predict employee attrition using real-world HR data.  
Visualized key attrition drivers such as salary, job satisfaction, and overtime using charts.  
This showcase-ready project delivers actionable insights for HR stakeholders.

---

## 📌 Project Objective

To analyze employee data and predict attrition using machine learning.  
The objective is to help HR teams identify at-risk employees and improve retention strategies.

---

## 🧰 Tools & Technologies

- **Python**
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

---

## 📂 Dataset

- **Source:** [IBM HR Analytics Employee Attrition & Performance – Kaggle](https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- Features include: Age, MonthlyIncome, OverTime, JobSatisfaction, WorkLifeBalance, and Attrition flag

---

## 🔍 Key Steps

1. **Data Cleaning & Encoding**
   - Converted `Attrition` to binary
   - Applied one-hot encoding to categorical features

2. **Exploratory Data Analysis (EDA)**
   - Visualized attrition by income, age, job satisfaction, overtime, and job role

3. **Model Training**
   - Used **Random Forest Classifier** to build a predictive model

4. **Model Evaluation**
   - Measured accuracy, precision, recall, and F1-score

5. **Feature Importance**
   - Extracted top features contributing to employee attrition

---

## 📊 Sample Insights

- Employees working **OverTime** are significantly more likely to leave.
- Low **Job Satisfaction** and **Monthly Income** strongly correlate with higher attrition.
- Top contributing features include:
  - `OverTime`
  - `JobLevel`
  - `MonthlyIncome`
  - `Age`

---

## ✅ Results

- **Model Used:** Random Forest Classifier
- **Performance:** High precision and recall on attrition cases
- **Output:** Classification report + Bar chart of top features

---

## 📁 Files Included

- `hr_attrition_project.py` – Full Python script (data processing, model training, evaluation)
- `README.md` – Project documentation

---

## 🙋‍♂️ Author

**Aadarsh Jaiswal**  
Data Analyst | Machine Learning Enthusiast  
📧 [aadarshjaiswal.vns@gmail.com](mailto:aadarshjaiswal.vns@gmail.com)  
🔗 [LinkedIn](https://linkedin.com/in/aadarsh-jaiswal)  
💻 [GitHub](https://github.com/aadarshjaiswalvns)

---

> ⭐ *If you found this project helpful, give it a star and share feedback!*
