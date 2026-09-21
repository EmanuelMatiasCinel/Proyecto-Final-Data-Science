# Grupo 16 - Proyecto Data Science
## Integrantes: Martín Nieto, Alejandra Melillo, Emanuel Cinel
## Semáforo Financiero: clasificación de empresas según sus ratios contables-financieros

**Objetivo:** construir un semáforo (Aceptable / Regular) que clasifique a cada empresa comparando sus ratios financiero-contables contra la media de su propio sector, año a año. A su vez poder predecir la Variación del año próximo que sufrirá el activo dado sus ratios financieros-contables.

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

**Importante:** el semáforo lo construimos nosotros a partir de los mismos ratios que después vamos a usar para describir a cada empresa.
