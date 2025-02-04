# Proyecto ETL: Datos del Clima de Guadalajara (Febrero 2020 - 2024)

Este proyecto tiene como objetivo realizar un proceso de ETL (Extract, Transform, Load) para datos climáticos de la ciudad de Guadalajara, México, utilizando datos obtenidos de Open Meteo. Los datos se procesan y almacenan en formato CSV, y se utiliza AWS Glue para la creación de crawlers y jobs que automatizan el proceso.

## Descripción del Proyecto

El proyecto consiste en los siguientes pasos:

1. **Extracción**: Descarga de datos climáticos históricos de Guadalajara desde Open Meteo para los meses de febrero desde 2020 hasta 2024.
2. **Transformación**: Limpieza y transformación de los datos para su posterior análisis.
3. **Carga**: Almacenamiento de los datos transformados en un bucket de S3 y uso de AWS Glue para catalogar los datos y ejecutar jobs de ETL.

## Requisitos

- Cuenta de AWS con acceso a S3, AWS Glue, y IAM.
- Python 3.x instalado.
- Biblioteca `requests` de Python para la descarga de datos.
- AWS CLI configurado con las credenciales adecuadas.
