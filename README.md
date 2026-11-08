# Ciencia y analítica de datos

Actividades del curso **TC5053 – Ciencia y analítica de datos** de la Maestría en Inteligencia Artificial Aplicada (Tecnológico de Monterrey). Cada carpeta contiene un notebook de Jupyter con el análisis y, cuando aplica, el conjunto de datos que usa.

## Actividades

| Semana | Tema | Datos | Técnicas y librerías |
| --- | --- | --- | --- |
| 2 | [Análisis de datos con pandas](<2.2 Actividad 2 - Análisis de datos con pandas>) | Datos meteorológicos 2020 (52 696 registros, cada 10 min) | Limpieza, tipos de datos, duplicados, fechas; `pandas`, `matplotlib` |
| 3 | [Acceso a bases de datos y manipulación](<3.2 Actividad 3 - Acceso BD y manipulación de datos>) | Base relacional del top 10 de Netflix | Consultas SQL desde Python; `PyMySQL`, `SQLAlchemy`, `pandas` |
| 4 | [Análisis exploratorio (EDA)](<4.2 Actividad 4 - EDA>) | `personal_loan.csv` (clientes bancarios) | Estadística descriptiva, distribuciones; `seaborn`, `scipy` |
| 5 | [Preprocesamiento](<5.2 Actividad 5 - Preprocesamiento>) | `heart_disease.csv` (variables clínicas) | Valores faltantes e imputación; `SimpleImputer` |
| 6 | [Ingeniería de características](<6.2 Actividad 6 - FE>) | `computer_prices.csv` (100 000 equipos) | Discretización, escalado, transformaciones de potencia, codificación (One-Hot, ordinal, binaria) |
| 8 | [Regresión lineal](<8.2 Actividad 8 - Regresión lineal>) | `diamonds_dataset.csv` (53 771 diamantes) | Pipelines con `scikit-learn`, características polinómicas, RMSE y R² |

Las actividades 6 y 8 se realizaron en equipo.

## Tecnologías

Python · Jupyter Notebook · pandas · NumPy · scikit-learn · seaborn · matplotlib · SQLAlchemy

## Cómo ejecutarlo

```bash
pip install pandas numpy matplotlib seaborn scipy scikit-learn category_encoders sqlalchemy pymysql jupyter
jupyter notebook
```

Abre el notebook de la actividad que quieras revisar; los archivos `.csv` están en la misma carpeta (la actividad 3 necesita acceso a una base de datos MySQL).
