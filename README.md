# Grupo 16 - Proyecto Data Science
## Integrantes: Martín Nieto, Alejandra Melillo, Emanuel Cinel
## Semáforo Financiero: clasificación de empresas según sus ratios contables-financieros

**Objetivo:** Predicción de la dirección anual del precio de acciones a partir de indicadores financiero-contables
Contenido: Parte I, análisis exploratorio (secciones 0 a 9). Parte II, modelo supervisado (sección 10). Se ejecuta de arriba hacia abajo: la Parte I genera financial_data_unificado.csv, que la Parte II vuelve a leer.

**Fuente de datos:** "200+ Financial Indicators of US stocks (2014-2018)", Kaggle, usuario Nicolas Carbone.
URL: https://www.kaggle.com/datasets/cnic92/200-financial-indicators-of-us-stocks-20142018

**Información de la Base de Datos:** Se tiene un conjunto de 5 bases de datos que luego se unificaron en un gran DataFrame, obteniendo así un total de:

**Dimensiones:** 22077 filas × 226 columnas

**Registros por año:**

| Año  | Registros |
|------|-----------|
| 2017 | 4960      |
| 2016 | 4797      |
| 2018 | 4392      |
| 2015 | 4120      |
| 2014 | 3808      |


