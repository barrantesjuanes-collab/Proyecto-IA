Título del Proyecto: Determinantes estructurales  de la fatalidad en accidentes de tránsito con víctimas en Colombia: un enfoque econométrico y de aprendizaje automático
Integrantes: Juan Esteban Barrantes, Juan Camilo Ordoñez, Miguel Andrés Rodríguez 
 
1. Definición del Problema y Objetivos
•	Objetivo: Desarrollar un modelo con los factores vehiculares y territoriales que determinan un accidente de tránsito con victimas mortales. Además, se busca comparar el desempeño productivo y la interpretación de modelos econométricos tradicionales frente a modelos avanzados de machine learning.
•	Descripción: La seguridad vial constituye un problema económico y social de alta relevancia, debido a los costos humanos, productivos y fiscales asociados a la siniestralidad. Desde la economía del riesgo, los accidentes de tránsito pueden entenderse como eventos asociados a decisiones individuales, calidad del capital vehicular y condiciones estructurales del entorno.
•	Entrega de Valor: El proyecto genera valor en tres dimensiones:
1.	Política pública: Permite identificar factores asociados a mayor probabilidad de fatalidad, lo cual puede orientar políticas de regulación vehicular, revisión técnico-mecánica, control a motocicletas o focalización territorial de intervenciones.
2.	Planeación y gestión territorial: El análisis de diferencias regionales puede contribuir a priorizar inversiones en infraestructura vial o fortalecer estrategias locales de seguridad.
3.	Metodología aplicada: El proyecto ejemplifica la aplicación de ciencia de datos e inteligencia artificial en economía, mostrando cómo los modelos predictivos pueden complementar el análisis econométrico tradicional en la toma de decisiones públicas.
2. Análisis de Stakeholders
•	Ministerio de Transporte de Colombia
•	Agencia Nacional de Seguridad Vial
•	Secretarías de Movilidad departamentales y municipales
•	Autoridades de tránsito
•	Aseguradoras
•	Centros de investigación en economía del transporte
•	Ciudadanía en general
3. Estrategia Técnica
•	Técnicas a utilizar: El proyecto se enmarca en la Ciencia de Datos y el Aprendizaje Supervisado, específicamente en un problema de clasificación binaria.
Se utilizará análisis exploratorio de datos (EDA), procesamiento para a limpieza de datos, validación cruzada para evitar sobreajuste, etc. Modelos de aprendizaje supervisado para regresión logística, arboles de decisión, random forest. Evaluación de modelos para matriz de confusión, accuracy, precisión y recall. Análisis de importancia de variables para comparación entre relevancia estadística e importancia predictiva.
4. Desafíos identificados
•	Sesgo de selección: La base no incluye accidentes sin víctimas, por lo que el análisis se restringe a la probabilidad condicional de fatalidad dado que ocurrió un accidente con víctimas. Esto limita la posibilidad de inferir riesgo total poblacional
•	Desbalance de clases: Es probable que los accidentes con muertos representen una proporción menor respecto a los accidentes con heridos, lo cual puede afectar el desempeño de los modelos. 
•	Alta dimensionalidad categórica: Variables como marca, modelo o municipio pueden generar un alto número de categorías, lo que requiere técnicas eficientes de codificación
•	Variables omitidas: No se cuenta con información directa sobre velocidad, condiciones climáticas o infraestructura vial específica, por lo que los efectos territoriales capturan factores estructurales no observados.
5. Variables Clave:
1.	Variable dependiente:
-	1=Con muertos
-	0=Con heridos
2.	Variables independientes:
-	Características vehiculares:
- Marca
- Modelo
- Tipo de vehiculo
- Edad de vehiculo
-	Características temporales 
- Fecha del accidente
-	Caracteristicas territoriales 
-Departamento
-Municipio
-Autoridad de tránsito
