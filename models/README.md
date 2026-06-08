# 🤖 Modelos de Machine Learning

## Descripción

Esta carpeta contiene los modelos de Machine Learning utilizados para la detección de amenazas de ciberseguridad en redes de Vehículos Aéreos No Tripulados (UAVs).

Los modelos fueron seleccionados con base en investigaciones previas relacionadas con Sistemas de Detección de Intrusiones (IDS) y detección de ataques en entornos UAV.

---

## Modelos Evaluados

### 🌳 Random Forest

Algoritmo basado en múltiples árboles de decisión que combina los resultados de cada árbol para mejorar la precisión y reducir el sobreajuste.

**Ventajas:**
- Alta precisión.
- Robusto frente a ruido.
- Fácil interpretación.

---

### ⚡ XGBoost

Extreme Gradient Boosting es un algoritmo de aprendizaje supervisado basado en árboles de decisión que construye modelos de forma secuencial para corregir errores de iteraciones anteriores.

**Ventajas:**
- Alta precisión en tareas de clasificación.
- Excelente rendimiento en datasets estructurados.
- Optimización eficiente del entrenamiento.
- Amplio uso en problemas de detección de intrusiones y ciberseguridad.

---

### 📈 Support Vector Machine (SVM)

Modelo supervisado que busca encontrar el hiperplano óptimo para separar diferentes clases de datos.

**Ventajas:**
- Buen rendimiento en espacios de alta dimensión.
- Eficiente para clasificación.

---

### 🧠 CNN + LSTM

Arquitectura híbrida que combina:

- CNN (Convolutional Neural Networks) para extracción de patrones locales.
- LSTM (Long Short-Term Memory) para capturar dependencias temporales.

**Ventajas:**
- Capacidad para identificar patrones complejos.
- Adecuado para tráfico de red con comportamiento secuencial.

---

## Objetivo de la Comparación

Los modelos son evaluados para determinar cuál ofrece el mejor desempeño en la detección de los ataques:

- Blackhole
- Flooding
- Sybil
- Wormhole

utilizando el dataset UAVIDS-2025.

---

## Métricas de Evaluación

- Accuracy
- Precision
- Recall
- F1-Score

---

