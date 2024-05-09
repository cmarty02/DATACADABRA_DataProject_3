Detección de Enfermedad Cardiaca

Introducción

Este proyecto se enfoca en identificar enfermedades cardíacas mediante el análisis de datos de varios pacientes con diferentes niveles de salud cardiovascular empleando técnicas de Machine Learningn 

Objetivos

El objetivo principal de este proyecto es desarrollar un modelo de aprendizaje automático de inteligencia artificial capaz de predecir la presencia de enfermedades cardíacas utilizando la información del dataset que se nos proporciona obtenida de diversas pruebas médicas y características clínicas.

Se busca proporcionar a los profesionales médicos una herramienta efectiva para la toma de decisiones clínicas y poder personalizar los tratamientos según las características individuales de cada paciente.

Equipo

 Cristian Marty, Pablo Pérez, Stas Korotchenko, Lucía Esteve

Dataset

El conjunto de datos está compuesto por 13 característicasque describen las condiciones de salud de cada uno de los pacientes. Estas características se describen a continuación:

Age: Edad del paciente 

Sex: Sexo del paciente
    0: Mujer
    1: Hombre

CP: Tipo de dolor de pecho 
    1: Angina típica
    2: Angina atípica
    3: Dolor no-anginoso
    4: Asintomático

Trestbps: Presión arterial en reposo (en mm Hg al ingreso en el hospital).

Chol: Colesterol sérico en mg/dl.

Fbs: Dolor provocado por el esfuerzo
    1 = sí
    0 = no
Restecg: Resultados electrocardiográficos en reposo:
    0: Normal
    1: Presenta anormalidad de la onda ST-T
    2: Presenta probable o definida hipertrofía ventricular izquierda

Thalach: Frecuencia cardiaca en reposo.

Exang: Angina inducida por el ejercicio
    1 = sí
    0 = no
Oldpeak: Depresión del ST inducida por el ejercicio en relación con el reposo.

Slope: La pendiente del segmento ST en ejercicio máximo:
    1: Pendiente ascendente
    2: Plano
    3: Pendiente descendente

Ca: Número de vasos mayores (0-3) coloreados por fluoroscopía.

Thal:
    3: Normal
    6: Defecto fijo
    7: Defecto reversible


Metodología

El desarrollo del proyecto sigue los siguientes pasos:

1. Análisis de Variables: Se realiza una exploración detallada de las variables para comprender su distribución y relevancia en el análisis.

2. Limpieza de Datos: Se lleva a cabo el proceso de limpieza de datos para eliminar valores atípicos y errores, asegurando la calidad y consistencia de los datos.

3. Imputación de Valores Faltantes: Se utilizan técnicas como el KNN imputer para imputar valores faltantes en las variables, garantizando la integridad de los datos para el análisis.

4. Preparación de Datos: Se transforman las variables categóricas en variables dummy para su inclusión en el modelo de aprendizaje automático.
Entrenamiento del Modelo: Se selecciona un conjunto de modelos de aprendizaje automático y se entrenan utilizando los datos preparados.

5. Benchmark de Modelos: Se realiza una evaluación comparativa de los modelos entrenados para identificar el más adecuado para el problema en cuestión.
   
6. Selección de Características: Se implementa el método de backward selection para identificar las características más relevantes y mejorar la eficiencia del modelo.
   
7. Iteración del Modelo: Se lleva a cabo un bucle de 1,000 iteraciones para refinar y optimizar el modelo seleccionado.

8. Métricas de Desempeño y Evaluación: Se utilizan métricas de rendimiento como precisión, recall y F1-score para evaluar el desempeño del modelo en la detección de enfermedades cardíacas.

9. Conclusiones y Hallazgos: Se discuten las conclusiones y hallazgos obtenidos durante el desarrollo del proyecto, destacando las limitaciones, posibles mejoras y el impacto potencial en la práctica clínica.
