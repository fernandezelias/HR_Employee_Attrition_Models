# 📊 Análisis de Rotación de Empleados (HR Employee Attrition)

🌐 Available in [English](README_EN.md)

Este proyecto aplica técnicas de **Machine Learning supervisado** para predecir la **renuncia de empleados (Attrition)** utilizando un dataset clásico de Recursos Humanos.  
El objetivo es identificar los factores más relevantes que influyen en la decisión de renunciar y comparar distintos modelos de clasificación.

---

## 🧰 Stack Tecnológico
- **Lenguaje:** Python 3.11  
- **Librerías:** Pandas, NumPy, Scikit-learn  
- **Visualización:** Matplotlib, Seaborn  
- **Entorno:** Jupyter Notebook  

---

## 🎯 Objetivos del proyecto
- Analizar variables demográficas, laborales y de satisfacción que puedan explicar la rotación del personal.  
- Entrenar y comparar tres modelos de clasificación supervisada:  
  1. **Árbol de Decisión (Decision Tree)**  
  2. **Bosque Aleatorio (Random Forest)**  
  3. **Regresión Logística (Logistic Regression)**  
- Evaluar el impacto del **desbalance de clases** (baja proporción de renuncias) y aplicar estrategias de compensación.

---

## ⚙️ Flujo de trabajo

1. **Carga y exploración de datos (EDA)**  
   - Limpieza de variables irrelevantes y tratamiento de datos categóricos.  
   - Visualización de distribuciones, correlaciones y patrones asociados a la renuncia.  

2. **Preparación y modelado**  
   - Codificación mediante *One-Hot Encoding* y división en conjuntos de entrenamiento y prueba.  
   - Entrenamiento de modelos con y sin balanceo (`class_weight='balanced'`).  

3. **Evaluación y comparación**  
   - Métricas utilizadas: *accuracy*, *precision*, *recall* y *f1-score*.  
   - Análisis de la importancia de variables y coeficientes según el modelo.  

---

## 📈 Resultados principales

| Modelo | Accuracy | Recall (Renuncia) | Interpretabilidad |
|:--|:--:|:--:|:--:|
| Árbol de Decisión | 0.76–0.77 | 0.28–0.34 | Alta |
| Bosque Aleatorio | 0.83–0.84 | 0.10–0.14 | Media |
| Regresión Logística | 0.72–0.86 | 0.27–0.68 | Alta |

- El **Bosque Aleatorio** logra la mayor precisión global y estabilidad.  
- La **Regresión Logística balanceada** incrementa notablemente la sensibilidad (*recall*) para la clase minoritaria.  
- El **Árbol de Decisión** ofrece la mejor interpretabilidad, pero menor capacidad predictiva.

---

## 🧠 Conclusiones generales

El análisis comparativo evidencia que el **desbalance de clases** afecta significativamente la detección de renuncias.  
Entre los modelos evaluados, la **Regresión Logística balanceada** logra el mejor equilibrio entre interpretabilidad y sensibilidad, mientras que el **Bosque Aleatorio** conserva la mejor precisión global.  

Este proyecto demuestra la aplicación completa del flujo de **Machine Learning supervisado** —desde la exploración y transformación de datos hasta la interpretación de modelos— y constituye un ejemplo base de clasificación binaria en entornos laborales.

---

## ✍️ Autor
**Elías Fernández**  
📧 Contacto: [fernandezelias86@gmail.com](mailto:fernandezelias86@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/eliasfernandez208)

---

📁 **Repositorio:** HR_Employee_Attrition_Models
