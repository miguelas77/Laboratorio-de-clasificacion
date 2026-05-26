# Laboratorio-de-clasificacion
# Clasificación de Clientes para Campaña Bancaria

Este proyecto desarrolla un análisis completo de clasificación usando el dataset `bank-full`, con el objetivo de predecir si un cliente aceptará o no una campaña de depósito bancario. El trabajo incluye análisis exploratorio de datos, preparación de variables, tratamiento de valores atípicos, balanceo de la variable dependiente, entrenamiento de modelos de clasificación y comparación final de resultados.

## Objetivo del proyecto

El objetivo principal es construir y evaluar diferentes modelos de clasificación que permitan predecir la variable dependiente `y`, la cual indica si un cliente aceptó o no el depósito ofrecido por la campaña bancaria.

La variable dependiente tiene dos posibles valores:

- `yes`: el cliente aceptó el depósito.
- `no`: el cliente no aceptó el depósito.

## Dataset utilizado

El dataset utilizado corresponde a información de campañas de marketing directo de una entidad bancaria. Contiene variables relacionadas con características personales, financieras, historial de contacto y resultados de campañas anteriores.

Algunas de las variables utilizadas son:

- `age`: edad del cliente.
- `job`: tipo de trabajo.
- `marital`: estado civil.
- `education`: nivel educativo.
- `default`: si el cliente tiene incumplimiento crediticio.
- `balance`: saldo promedio anual.
- `housing`: si tiene crédito de vivienda.
- `loan`: si tiene préstamo personal.
- `contact`: tipo de contacto.
- `day`: día del contacto.
- `month`: mes del contacto.
- `duration`: duración de la llamada.
- `campaign`: número de contactos durante la campaña.
- `pdays`: días desde el último contacto.
- `previous`: número de contactos previos.
- `poutcome`: resultado de campañas anteriores.
- `y`: variable dependiente.

## Tecnologías utilizadas

El proyecto fue desarrollado usando Python y PySpark dentro de un entorno de notebook.

Las principales librerías utilizadas fueron:

```python
pyspark
pandas
numpy
matplotlib
seaborn
scikit-learn
