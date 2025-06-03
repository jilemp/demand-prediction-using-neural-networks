# 📦 Predicción de Demanda con Redes Neuronales
Este repositorio presenta un proyecto final enfocado en la predicción de demanda para componentes de maquinaria utilizando técnicas de aprendizaje automático, con énfasis principal en redes neuronales. Desarrollado como parte del programa de Ciencia de Datos y Machine Learning de **4Geeks Academy**, este proyecto demuestra cómo modelos avanzados pueden optimizar inventarios y reducir costos.

---

## 📁 Contenido del Proyecto

```
├── project_notebook.ipynb       # Notebook completo con preprocesamiento, modelado y evaluación
├── Predicción_de_Demanda.pdf    # Informe final del proyecto (en español)
├── data/                        # (Opcional) Conjuntos de datos utilizados para el modelado
├── README.md                    # Descripción general e instrucciones del proyecto
```

---

## 🧠 Contexto del Problema

La empresa:

- Está ubicada en Ecuador y suministra repuestos de maquinaria a la industria alimentaria.  
- Obtiene productos de Asia y Europa, con largos tiempos de envío.  
- Busca optimizar inventarios prediciendo la demanda a partir de variables internas y externas.  

---

## 📊 Descripción de los Datos

- 📅 Rango Histórico: 2021–2024  
- 🛍 Número de SKUs: 1,105 ítems únicos  
- 📄 Transacciones: 3,605 totales  
- 💡 Variables incluidas: ventas, compras, tipos de productos, y factores macroeconómicos como:  
  - Precio del Petróleo Brent  
  - IPC de Ecuador  
  - PIB de Ecuador  

---

## 🔍 Metodología

**Enfoque de ML:** Redes Neuronales usando `MLPRegressor`  

**Arquitectura del modelo:**
- 8 capas ocultas con 100 neuronas cada una  
- Activación: ReLU  
- Optimizador: LBFGS  
- Ajuste de hiperparámetros: GridSearch y Validación Cruzada  

📈 Otros modelos evaluados:  
- Regresión Logística  
- AdaBoost  
- KNN  
- SVC  
- Random Forest  

---

## 📌 Resultados

- 🔍 MAE: 12.39  
- 🎯 Impacto:
  - Reducción de sobreinventario  
  - Mejora en la precisión del pronóstico  
  - Optimización del inventario  

---

## 📈 Mejoras Futuras

- Incluir estacionalidad, promociones, competencia y tasas de cambio.  
- Mejorar la ingeniería de características y explorar nuevas arquitecturas de modelos.  
- Implementar reentrenamiento automático del modelo para entornos de inventario dinámicos.  

---

## 🚀 Cómo Empezar

**Requisitos Previos**  
Instala las dependencias:

```bash
pip install -r requirements.txt
```

**Ejecutar el notebook**

```bash
jupyter notebook project_notebook.ipynb
```

---

## 📚 Referencias

- [Investing.com – Precios del Petróleo Brent (2021–2024)]  
- [Trading Economics – PIB e IPC de Ecuador]  
- [Documentación de Scikit-learn para MLPRegressor]  

---

## 👥 Autores

- Alfonzo Gonzalez  
- Andrés Cabrales  
- José Ignacio Ibarra  

🎓 Desarrollado como parte del programa de Ciencia de Datos y Machine Learning de **4Geeks Academy**
