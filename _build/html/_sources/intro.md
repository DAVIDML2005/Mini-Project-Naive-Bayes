# **Introducción al Proyecto**

Las enfermedades cardiovasculares constituyen una de las principales causas de mortalidad a nivel global. La capacidad de predecir la presencia de enfermedades cardíacas a partir de atributos clínicos y demográficos de un paciente representa una herramienta invaluable para el sector salud, permitiendo diagnósticos tempranos y intervenciones preventivas. 

El presente estudio utiliza el dataset **Heart Disease** de la UCI Machine Learning Repository, que contiene información de 303 pacientes y 76 atributos, aunque el subconjunto más comúnmente utilizado contiene 14 características clave. El objetivo de este análisis es desarrollar un modelo de clasificación predictivo que, con base en variables clínicas y demográficas, determine la presencia o ausencia de cardiopatía.

El proceso seguirá un flujo de trabajo de ciencia de datos que incluye la exploración y limpieza de datos, análisis univariado y multivariado, preprocesamiento, modelado con diversos algoritmos y la evaluación rigurosa del desempeño de cada uno para identificar el mejor predictor.

## **Variables de Estudio**

**Variables Demográficas:**
- `age`: Edad del paciente en años.
- `sex`: Sexo del paciente (binaria: 0 = femenino, 1 = masculino).

**Variables Clínicas y Sintomatología:**
- `cp`: Tipo de dolor torácico:
  - 1 = angina típica
  - 2 = angina atípica 
  - 3 = dolor no anginoso
  - 4 = asintomático
- `trestbps`: Presión arterial en reposo (mm Hg).
- `chol`: Colesterol sérico (mg/dl).
- `fbs`: Azúcar en ayunas > 120 mg/dl (binaria: 0 = no, 1 = sí).
- `restecg`: Resultados electrocardiográficos en reposo:
  - 0 = normal
  - 1 = anormalidad ST-T
  - 2 = hipertrofia ventricular izquierda
- `thalach`: Frecuencia cardíaca máxima alcanzada.
- `exang`: Angina inducida por ejercicio (binaria: 0 = no, 1 = sí).
- `oldpeak`: Depresión del ST inducida por ejercicio relative al reposo.

**Variables de Pruebas Diagnósticas:**
- `slope`: Pendiente del segmento ST de ejercicio máximo:
  - 1 = ascendente
  - 2 = plana
  - 3 = descendente
- `ca`: Número de vasos principales coloreados por fluoroscopia (0-3, numérica).
- `thal`: Talasemia (defecto sanguíneo):
  - 3 = normal
  - 6 = defecto fijo
  - 7 = defecto reversible

**Variable Objetivo:**
- `num`: Diagnóstico de enfermedad cardíaca (binaria: 0 = ausencia, 1 = presencia).

Este conjunto de variables abarca desde características demográficas básicas hasta resultados de pruebas médicas especializadas, proporcionando una base comprehensiva para el desarrollo de modelos predictivos de enfermedad cardiovascular.