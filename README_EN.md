# 📊 Employee Attrition Analysis (HR Analytics)

🌐 Available in: [Español](README.md)

This project applies **supervised Machine Learning** techniques to predict **employee attrition**, using a classical Human Resources dataset.  
The goal is to identify the main factors influencing resignation decisions and to compare the performance of different classification models.

---

## 🎯 Project Objectives
- Analyze demographic, workplace, and satisfaction-related variables that explain employee turnover.  
- Train and compare three supervised classification models:  
  1. **Decision Tree**  
  2. **Random Forest**  
  3. **Logistic Regression**  
- Assess the impact of **class imbalance** (few resignations) and test balancing strategies.

---

## ⚙️ Workflow

1. **Data loading and exploration (EDA)**  
   - Removal of irrelevant features and encoding of categorical data.  
   - Visualization of distributions, correlations, and patterns associated with attrition.  

2. **Preparation and modeling**  
   - One-Hot Encoding and train-test split.  
   - Model training with and without balancing (`class_weight='balanced'`).  

3. **Evaluation and comparison**  
   - Metrics: *accuracy*, *precision*, *recall*, and *f1-score*.  
   - Analysis of feature importance and coefficients for interpretability.  

---

## 📈 Key Results

| Model | Accuracy | Recall (Attrition) | Interpretability |
|:--|:--:|:--:|:--:|
| Decision Tree | 0.76–0.77 | 0.28–0.34 | High |
| Random Forest | 0.83–0.84 | 0.10–0.14 | Medium |
| Logistic Regression | 0.72–0.86 | 0.27–0.68 | High |

- **Random Forest** achieved the highest overall accuracy and model stability.  
- **Balanced Logistic Regression** significantly improved recall for the minority class.  
- **Decision Tree** offered excellent interpretability but lower predictive performance.

---

## 🧠 General Conclusions

The comparison confirms that **class imbalance** strongly impacts minority detection.  
Among all models, **Balanced Logistic Regression** achieved the best trade-off between interpretability and sensitivity, while **Random Forest** maintained the highest global precision.  

This project demonstrates the complete **supervised Machine Learning pipeline** —from data exploration and transformation to model interpretation— serving as a baseline example for binary classification in HR analytics.

---

## 🧰 Technologies Used
- Python 3.11  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## ✍️ Author
**Elías Fernández**  
📧 Contact: [fernandezelias86@gmail.com](mailto:fernandezelias86@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/eliasfernandez208)

---

📁 **Repository:** HR_Employee_Attrition_Models  
