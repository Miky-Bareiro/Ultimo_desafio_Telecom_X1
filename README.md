Análisis y predicción de Churn en Clientes de TELECOM_X
Descripción del Proyecto
Este proyecto de ciencia de datos se enfoca en la predicción del abandono de clientes ( churn) de una empresa de TELECOM_X. 
El objetivo principal es identificar a los clientes con alto riesgo de irse para implementar estrategias de retención. 
Se construyeron y evaluaron varios modelos de aprendizaje automático para encontrar el que mejor se adaptará al problema, priorizando el recallsobre la precisión.

¿Qué se hizo?

Carga y exploración de datos

Lectura del conjunto de datos.
Análisis de la distribución de la variable objetivo ( Churn).
Visualizaciones de variables categóricas y numéricas.
Preparación de datos

Eliminación de columnas irrelevantes ( customerID).
Transformación de variables categóricas a numéricas con OneHotEncoding.
Separación en conjuntos de entrenamiento y prueba.
Modelado

Entrenamiento con Regresión Logística.
Entrenamiento con Random Forest.
Comparación con y sin balanceo de clases mediante SMOTE .
Evaluación de modelos

Métricas: Accuracy, Precision, Recall y AUC.
Tabla resumen de resultados.
Predicciones

Selección aleatoria de registros del conjunto de datos.
predicción de probabilidad de abandono para cada uno.
Conclusiones

Identificación del modelo con mejor desempeño.
Observaciones sobre el desequilibrio de clases y el impacto de SMOTE.

Tecnologías y Librerías
Lenguaje: Python
Librerías:
pandas: Manipulación y análisis de datos.
numpy: Cálculo numérico.
scikit-learn: Modelado y evaluación de aprendizaje automático .
imblearn: Manejo de desequilibrio de clases ( SMOTE).
matplotliby seaborn: Visualización de datos y resultados.
