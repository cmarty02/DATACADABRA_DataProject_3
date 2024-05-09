# Detección de Enfermedad Cardiaca
## Equipo

 Lucía Esteve, Cristian Marty, Pablo Pérez y Stas Korotchenko.

## Introducción

Este proyecto se enfoca en identificar enfermedades cardíacas mediante el análisis de datos de varios pacientes con diferentes niveles de salud cardiovascular empleando técnicas de Machine Learning.

## Objetivos

El objetivo principal de este proyecto es desarrollar un modelo de aprendizaje automático de inteligencia artificial capaz de predecir la presencia de enfermedades cardíacas utilizando la información del dataset que se nos proporciona obtenida de diversas pruebas médicas y características clínicas.

Se busca proporcionar a los profesionales médicos una herramienta efectiva para la toma de decisiones clínicas y poder personalizar los tratamientos según las características individuales de cada paciente.

## Dataset

El conjunto de datos está compuesto por 13 características que describen las condiciones de salud de cada uno de los pacientes. Estas características se describen a continuación:

- Age: Edad del paciente 
- Sex: Sexo del paciente (0: Mujer, 1: Hombre)
- CP: Tipo de dolor de pecho 
- Trestbps: Presión arterial en reposo (en mm Hg al ingreso en el hospital)
- Chol: Colesterol sérico en mg/dl
- Fbs: Dolor provocado por el esfuerzo (1 = sí, 0 = no)
- Restecg: Resultados electrocardiográficos en reposo
- Thalach: Frecuencia cardiaca en reposo
- Exang: Angina inducida por el ejercicio (1 = sí, 0 = no)
- Oldpeak: Depresión del ST inducida por el ejercicio en relación con el reposo
- Slope: La pendiente del segmento ST en ejercicio máximo
- Ca: Número de vasos mayores (0-3) coloreados por fluoroscopía
- Thal: Tipo de defecto (3: Normal, 6: Defecto fijo, 7: Defecto reversible)

## Metodología

El desarrollo del proyecto sigue los siguientes pasos:

1. Análisis de Variables: Se realiza una exploración detallada de las variables para comprender su distribución y relevancia en el análisis.

2. Limpieza de Datos: Se lleva a cabo el proceso de limpieza de datos para eliminar valores atípicos y errores, asegurando la calidad y consistencia de los datos.

3. Imputación de Valores Faltantes: Se utilizan técnicas como el KNN imputer para imputar valores faltantes en las variables, garantizando la integridad de los datos para el análisis.

4. Preparación de Datos: Se transforman las variables categóricas en variables dummy para su inclusión en el modelo de aprendizaje automático.

5. Entrenamiento del Modelo: Se selecciona un conjunto de modelos de aprendizaje automático y se entrenan utilizando los datos preparados.

6. Benchmark de Modelos: Se realiza una evaluación comparativa de los modelos entrenados para identificar el más adecuado para el problema en cuestión.

7. Selección de Características: Se implementa el método de backward selection para identificar las características más relevantes y mejorar la eficiencia del modelo.

8. Iteración del Modelo: Se lleva a cabo un bucle de 1,000 iteraciones para refinar y optimizar el modelo seleccionado.

9. Métricas de Desempeño y Evaluación: Se utilizan métricas de rendimiento como precisión, recall y F1-score para evaluar el desempeño del modelo en la detección de enfermedades cardíacas.

10. Conclusiones y Hallazgos: Se discuten las conclusiones y hallazgos obtenidos durante el desarrollo del proyecto, destacando las limitaciones, posibles mejoras y el impacto potencial en la práctica clínica.
