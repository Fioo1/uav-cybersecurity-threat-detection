# 📊 Dataset Utilizado

## UAVIDS-2025

El presente proyecto utiliza el dataset **UAVIDS-2025**, desarrollado para la investigación y evaluación de sistemas de detección de intrusiones en redes de Vehículos Aéreos No Tripulados (UAVs).

El conjunto de datos contiene aproximadamente **122,171 registros de tráfico de red UAV**, clasificados en cinco categorías de comportamiento.

### Categorías del Dataset

- Normal Traffic
- Blackhole Attack
- Flooding Attack
- Sybil Attack
- Wormhole Attack

---

## Descripción

El dataset fue generado mediante entornos de simulación especializados para redes UAV y permite analizar patrones de tráfico normales y maliciosos presentes durante la operación de drones.

Su objetivo es facilitar el desarrollo y evaluación de modelos de Machine Learning orientados a la detección de amenazas de ciberseguridad.

---

## Uso dentro del Proyecto

En esta investigación, el dataset UAVIDS-2025 será utilizado para:

- Entrenar modelos de Machine Learning.
- Evaluar el desempeño de algoritmos de clasificación.
- Detectar amenazas en redes UAV.
- Comparar diferentes técnicas de detección de intrusiones.
- Analizar métricas como Accuracy, Precision, Recall y F1-Score.

---

## Preprocesamiento Aplicado

Antes del entrenamiento de los modelos se realizan las siguientes actividades:

- Verificación de valores nulos.
- Verificación de registros duplicados.
- Codificación de etiquetas.
- Normalización de variables mediante StandardScaler.
- División estratificada en conjuntos de entrenamiento y prueba.

---

## Referencia

Zeng et al. (2025). UAVIDS-2025 Dataset.
