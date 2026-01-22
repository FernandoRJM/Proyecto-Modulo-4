# Segmentación de Clientes con Clustering (K-Means)

## 📝 Descripción
Este proyecto aplica técnicas de Aprendizaje No Supervisado para segmentar clientes basándose en su comportamiento de compra y perfil demográfico. El objetivo es identificar grupos con características similares para permitir que el departamento de marketing diseñe estrategias personalizadas y eficientes.

## 🛠️ Herramientas y Tecnologías
• Lenguaje: Python 3.x 
• Librerías: Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn. 
• Algoritmos: K-Means Clustering. 
• Técnicas: Método del Codo (Elbow Method), Escalado de datos (StandardScaler), Análisis de centroides.

## 📊 Dashboard / Resultados
•⁠  ⁠A través del análisis de los datos, se determinaron los siguientes puntos clave:

1. Número Óptimo de Grupos: Mediante el Método del Codo, se identificó que K=4 es la cantidad ideal de clusters, logrando un equilibrio entre la cohesión interna de los grupos y la complejidad del modelo.

2. Perfil de los Segmentos:

- Cluster 0: Clientes de ingresos medios con gasto moderado.
- Cluster 1: Clientes con ingresos altos pero bajo nivel de gasto (Potencial de crecimiento).
- Cluster 2: Clientes de ingresos bajos y bajo gasto.
- Cluster 3: Clientes estrella (Ingresos altos y gasto alto).

3. Visualización: Se generaron gráficos de dispersión que muestran una clara separación entre los grupos, facilitando la interpretación del comportamiento de cada segmento.
