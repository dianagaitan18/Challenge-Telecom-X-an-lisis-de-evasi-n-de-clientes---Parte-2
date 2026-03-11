Predicción de Cancelación de Clientes (Churn) - Telecom X

 Descripción del proyecto

Este proyecto tiene como objetivo analizar el comportamiento de los clientes de una empresa de telecomunicaciones y desarrollar modelos de **Machine Learning** que permitan **predecir la cancelación de clientes (churn)**.

A través del análisis de datos y la creación de modelos predictivos, se busca identificar los factores que influyen en la cancelación del servicio y proponer estrategias que ayuden a **mejorar la retención de clientes**.


Objetivos

* Analizar los datos de clientes de Telecom X.
* Identificar patrones asociados con la cancelación del servicio.
* Construir modelos predictivos para estimar la probabilidad de churn.
* Evaluar el desempeño de los modelos mediante métricas de clasificación.
* Proponer estrategias de retención basadas en los resultados obtenidos.



 Dataset

El dataset contiene información sobre clientes de una empresa de telecomunicaciones, incluyendo variables como:

* Datos demográficos de los clientes
* Servicios contratados
* Tipo de contrato
* Método de pago
* Cargos mensuales y totales
* Variable objetivo: **Churn (cancelación del servicio)**


 Tecnologías utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

Metodología

Limpieza y preparación de datos

* Eliminación de columnas irrelevantes
* Conversión de variables categóricas mediante **One-Hot Encoding**
* Manejo de valores faltantes
* Análisis exploratorio de datos

Análisis exploratorio

Se realizaron diferentes visualizaciones para entender el comportamiento de los clientes, tales como:

* Relación entre tiempo de permanencia y cancelación
* Análisis del gasto total de los clientes
* Matriz de correlación entre variables

 Modelos predictivos

Se desarrollaron dos modelos de clasificación:

**Regresión Logística**

* Se aplicó normalización de datos
* Modelo sensible a la escala de las variables

**Random Forest**

* Modelo basado en árboles de decisión
* No requiere normalización

 Evaluación de modelos

Los modelos se evaluaron utilizando las siguientes métricas:

* Accuracy
* Precision
* Recall
* F1-score
* Matriz de confusión



Resultados

Los resultados muestran que la **Regresión Logística obtuvo un mejor desempeño general**, logrando una mayor exactitud y mejor equilibrio entre precisión y recall en comparación con el modelo Random Forest.

Entre las variables más relevantes para predecir la cancelación se encuentran:

* Tiempo de permanencia del cliente (tenure)
* Tipo de contrato
* Cargos mensuales
* Tipo de servicio de internet
* Método de pago

 Conclusiones

El análisis permitió identificar que los clientes con **contratos mensuales, poco tiempo en la empresa y cargos mensuales elevados** presentan una mayor probabilidad de cancelar el servicio.

El uso de modelos predictivos permite a la empresa **anticipar posibles cancelaciones** y desarrollar estrategias de retención más efectivas.



 Estrategias recomendadas

* Incentivar contratos de largo plazo.
* Implementar programas de fidelización para clientes nuevos.
* Mejorar la experiencia del servicio para clientes con cargos altos.
* Ofrecer beneficios personalizados según el perfil del cliente.


