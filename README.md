# Ejercicios Transversales: Procesamiento de Datos Meteorológicos

Este repositorio contiene la resolución de los ejercicios transversales de la materia **Programación II**. El objetivo principal es la lectura, limpieza, manipulación y análisis exploratorio de datos meteorológicos provenientes de diversas estaciones de medición.

## Herramientas y Librerías

El proyecto está desarrollado en **R** dentro del entorno **RStudio**, utilizando el ecosistema `tidyverse` y sus principales librerías:

* `readr`: Importación y lectura de archivos CSV.
* `dplyr`: Manipulación, filtrado, transformación y resumen de datos.
* `lubridate`: Manejo y procesamiento eficiente de fechas y horas.

## Estructura del Proyecto

* `transversales_proII.Rproj`: Archivo de configuración del proyecto de RStudio.
* `lectura_datos_meteorologicos.qmd`: Archivo donde se realiza la importación de archivos de metadatos y estaciones mediante `read_csv()`.
* `manipulacion_datos_meteorologicos.qmd`: Archivo enfocado en la resolución de ejercicios de filtrado, transformación y análisis de variables.
* `datos/`:
  * `crudos/`: Contiene los archivos `.csv` originales de las estaciones meteorológicas y los metadatos.
  * `derivados/`: Destinada a guardar conjuntos de datos procesados o limpios (actualmente vacía).
* `scripts/`: Carpeta para scripts auxiliares (actualmente vacía).
* `resultados/`: Carpeta para exportación de tablas, reportes o productos finales (actualmente vacía).

## Integrantes

* Paulina Guerscovich
* Manuela Bulgubure