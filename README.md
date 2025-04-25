# Análisis de Datos de Salarios con Pandas

Este repositorio contiene un análisis de datos de salarios de empleados usando la biblioteca Pandas de Python. El análisis se realiza sobre un conjunto de datos que contiene información salarial de empleados públicos.

## Descripción

Este proyecto analiza un conjunto de datos de salarios empleando DataFrames de Pandas y SQLite para obtener distintas métricas e información relevante. El conjunto de datos incluye información como nombres de empleados, cargos, salarios base, horas extra, beneficios y salarios totales.

## Funcionalidades implementadas

El análisis incluye las siguientes operaciones:

1. **Top 10 empleados con mayor salario total** - Identificación de los empleados mejor remunerados incluyendo beneficios.
2. **Filtrado de empleados con horas extra elevadas** - Selección de empleados que han cobrado más de $50,000 en horas extra.
3. **Conteo de empleados únicos por año** - Análisis de la cantidad de empleados únicos registrados en cada año.
4. **Análisis de cargos** - Identificación del número total de cargos únicos y los 5 más comunes.
5. **Salario promedio anual** - Cálculo del salario total promedio por año.
6. **Exportación de datos** - Exportación del conjunto de datos completo a un archivo CSV.

## Tecnologías utilizadas

- Python 3
- Pandas
- SQLite
- Jupyter Notebook

## Estructura del proyecto

```
pandas_df_tlp3_Mauricio_Heredia/
│
├── actividad_df.ipynb     # Notebook principal con el análisis
├── Salaries.sqlite        # Base de datos SQLite con información de salarios
├── actividad_df.csv       # Archivo CSV exportado con todos los datos
└── README.md              # Este archivo
```

## Cómo ejecutar

1. Clona este repositorio en tu máquina local
2. Asegúrate de tener instaladas las dependencias necesarias:
   ```
   pip install pandas jupyter sqlite3
   ```
3. Abre el archivo `actividad_df.ipynb` en Jupyter Notebook:
   ```
   jupyter notebook actividad_df.ipynb
   ```
4. Ejecuta las celdas del notebook para ver los resultados del análisis

## Resultados destacados

- El empleado con mayor salario total es NATHANIEL FORD con $567,595.43
- Existen 2,159 cargos únicos en la base de datos
- El cargo más común es "Transit Operator" con 7,036 empleados
- El salario promedio más alto se registró en 2013 con $77,611.44

## Criterios de desarrollo

Este proyecto se ha desarrollado siguiendo los siguientes criterios:

- Uso de nombres de variables descriptivos y claros
- Código comentado de manera concisa explicando el propósito de cada sección
- Mensajes de commit descriptivos utilizando la convención adecuada
- Formato de entrega según los requisitos especificados

## Autor

Mauricio Heredia

## Licencia

Este proyecto está bajo la Licencia MIT.
