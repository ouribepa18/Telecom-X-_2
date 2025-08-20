# 📊 Predicción de Cancelación de Clientes (Churn) – TelecomX

Este proyecto desarrolla un **pipeline de Machine Learning** para predecir la cancelación de clientes en una empresa de telecomunicaciones (**TelecomX**).  

El objetivo es identificar los factores que más influyen en el **churn** y construir modelos predictivos que permitan diseñar **estrategias de retención**.

---

## 📌 Objetivos del Proyecto
- Preparar los datos para el modelado (tratamiento, codificación, normalización).
- Realizar análisis de correlación y selección de variables.
- Entrenar y comparar varios modelos de clasificación.
- Evaluar el rendimiento con métricas como **ROC AUC, PR AUC, F1, Accuracy**.
- Interpretar los resultados, destacando la importancia de las variables.
- Generar una conclusión estratégica con recomendaciones de negocio.

---

## 🛠️ Tecnologías Utilizadas
- **Python 3**
- **Pandas, Numpy** → Manejo de datos  
- **Matplotlib, Seaborn** → Visualización  
- **Scikit-learn** → Preprocesamiento y modelado  
- **Imbalanced-learn (SMOTE)** → Balanceo de clases  
- **XGBoost** → Modelo avanzado de clasificación  

---

## 📂 Estructura del Proyecto
```
├── TelecomX_2.ipynb   # Notebook principal con el análisis y modelado
├── datos_telecomx.csv # Dataset (no incluido por privacidad)
├── README.md          # Documentación del proyecto
├── requirements.txt   # Dependencias necesarias
```

---

## 📈 Resultados Principales
- Los modelos probados incluyen **Regresión Logística, Random Forest y XGBoost**.  
- **XGBoost y Random Forest** alcanzaron las mejores métricas en **ROC AUC y PR AUC**.  
- Se identificaron los factores más influyentes en la cancelación:
  - Tipo de contrato (mensual vs. anual).  
  - Ausencia de servicios adicionales.  
  - Método de pago (mensual vs. automático).  
  - Monto mensual facturado.  

---

## 🎯 Conclusión Estratégica
- Promover **contratos de mayor duración** con beneficios claros.  
- Diseñar campañas de **cross-selling** para incrementar servicios adicionales.  
- Incentivar el uso de **pagos automáticos**.  
- Ajustar precios de planes altos ofreciendo beneficios diferenciados.  

Estas estrategias permiten **reducir el churn y aumentar la retención de clientes**.  


---

## 📧 Contacto
📩 Autor: *Olfer Andres Uribe Palomino*  
🔗 LinkedIn: [tu-linkedin](https://www.linkedin.com/in/olfer-andres-uribe-palomino)  
