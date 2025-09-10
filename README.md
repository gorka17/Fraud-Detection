# Fraud-Detection

Este proyecto se centra en el desarrollo de un sistema de detección de fraudes bancarios en pagos con tarjeta de crédito utilizando técnicas de Machine Learning. El dataset empleado es de gran tamaño (aprox. dos millones de transacciones) y altamente desbalanceado, lo que supone un reto significativo: la enorme mayoría de registros corresponden a operaciones legítimas, mientras que los casos de fraude representan una fracción mínima.

El trabajo se ha estructurado en varias fases:

- Análisis exploratorio de datos (EDA): permitió identificar patrones relevantes y posibles problemas en la distribución de las variables, además de guiar la posterior creación de nuevas variables sintéticas para enriquecer la representación de los datos.

- Entrenamiento metódico de modelos: se probaron desde algoritmos base como Decision Trees y Random Forests, hasta modelos más sofisticados como XGBoost, pasando por enfoques especializados en desbalance como Balanced Random Forest y el uso de redes de Deep Learning.

- Manejo del desbalance: se aplicaron técnicas específicas para mitigar los problemas derivados de la desproporción entre clases, mejorando la capacidad de los modelos para detectar fraudes. Se han considerado Random Over/Under Sampling y SMOTE.

La realización de este proyecto me ha ayudado a:

- Trabajar con un dataset realista, grande y complejo, en un ámbito tan interesante y útil como el de la detección de fraudes.

- Enfrentar el reto del desbalance de clases y seleccionar métricas adecuadas para evaluar el rendimiento, como AUC, recall, precision o F1-score entre otros.

- Organizar de forma estructurada la experimentación con distintos algoritmos y comparar sus resultados para seleccionar el que tenga un mayor impacto en la detección de transacciones ilegítimas.

- Comprender mejor la importancia del feature engineering y la calidad de los datos en el éxito de los modelos, habiendo dedicado gran parte del proyecto a comprender y analizar el dataset además de crear variables sintéticas.

En conjunto, este trabajo me ha ayudado a desarrollar un sistema experimental de detección de fraudes y a adquirir una visión práctica de cómo abordar problemas reales de Machine Learning de forma rigurosa y con un enfoque metódico.
