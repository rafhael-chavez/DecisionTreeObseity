# DecisionTreeObseity
# Proyecto de Árboles de Decisión para Predicción de Obesidad

Este proyecto utiliza un modelo de árboles de decisión para predecir el nivel de obesidad basado en un conjunto de características como género, edad, altura, peso, historial familiar, consumo de alcohol y tabaco, y actividad física. El objetivo es clasificar a las personas en uno de los siete niveles de obesidad.

## Descripción del Dataset

El dataset utilizado contiene las siguientes características:
- `gender`: Género de la persona.
- `age`: Edad de la persona.
- `height`: Altura en centímetros.
- `weight`: Peso en kilogramos.
- `family_history`: Historia familiar de sobrepeso (Sí/No).
- `workout`: Actividad física regular (Sí/No).
- `alcochol`: Consumo de alcohol (Sí/No).
- `smoke`: Consumo de tabaco (Sí/No).
- `NObeyesdad`: Clase objetivo que clasifica el nivel de obesidad en:
  - `Insufficient_Weight`
  - `Normal_Weight`
  - `Overweight_Level_I`
  - `Overweight_Level_II`
  - `Obesity_Type_I`
  - `Obesity_Type_II`
  - `Obesity_Type_III`

## Instalación

Para ejecutar este proyecto, necesitarás tener instaladas las siguientes librerías de Python:

```bash
pip install pandas scikit-learn matplotlib seaborn
