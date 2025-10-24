# 📊 Employee Attrition Analysis – Classification Models

🌐 Available in Spanish: [README.md](README.md)

This project applies **supervised Machine Learning techniques** to predict **employee attrition** using a classic Human Resources dataset.  
The goal is to identify key factors influencing resignation decisions and compare several classification models.

---

## 🧰 Tech Stack
- **Language:** Python 3.11  
- **Libraries:** Pandas, NumPy, Scikit-learn  
- **Visualization:** Matplotlib, Seaborn  
- **Environment:** Jupyter Notebook  

---

## 🎯 Project Goals
- Analyze demographic, work, and satisfaction variables that explain employee turnover.  
- Train and compare three supervised classification models:  
  1. **Decision Tree**  
  2. **Random Forest**  
  3. **Logistic Regression**  
- Evaluate the impact of **class imbalance** (low attrition rate) and apply balancing strategies.

---

## ⚙️ Workflow

1. **Data Loading and Exploration (EDA)**  
   - Clean irrelevant variables and handle categorical data.  
   - Visualize distributions, correlations, and patterns related to attrition.  

2. **Preparation and Modeling**  
   - Encode categorical variables using *One-Hot Encoding* and split data into train/test sets.  
   - Train models with and without balancing (`class_weight='balanced'`).  

3. **Evaluation and Comparison**  
   - Metrics used: *accuracy*, *precision*, *recall*, and *f1-score*.  
   - Analyze feature importance and model coefficients.

---

## 📈 Main Results

| Model | Accuracy | Recall (Attrition) | Interpretability |
|:--|:--:|:--:|:--:|
| Decision Tree | 0.76–0.77 | 0.28–0.34 | High |
| Random Forest | 0.83–0.84 | 0.10–0.14 | Medium |
| Logistic Regression | 0.72–0.86 | 0.27–0.68 | High |

- The **Random Forest** achieved the highest global accuracy and robustness.  
- The **Balanced Logistic Regression** significantly improved recall for the minority class.  
- The **Decision Tree** provided the most interpretability but lower predictive power.

---

## 🧠 General Conclusions

The comparative analysis shows that **class imbalance** strongly affects attrition detection.  
Among the evaluated models, the **Balanced Logistic Regression** achieves the best trade-off between interpretability and sensitivity, while the **Random Forest** maintains the best overall accuracy.  

This project demonstrates the full **supervised ML workflow** —from data exploration and preprocessing to model interpretation— and serves as a foundational example of binary classification in HR analytics.

---

## ✍️ Author
**Elías Fernández**  
📧 Contact: [fernandezelias86@gmail.com](mailto:fernandezelias86@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/eliasfernandez208)

---

📁 **Repository:** HR_Employee_Attrition_Models
