### 📝 Descripción de la actividad

Esta actividad se realizó en el entorno **Databricks (Free Edition)** utilizando **PySpark**, con el objetivo de aplicar los fundamentos del **Big Data** en la creación, manipulación y consulta de grandes volúmenes de información.  

El trabajo se desarrolló empleando el dataset **Top Anime Dataset** obtenido desde Kaggle, el cual contiene datos sobre los animes más populares, incluyendo su posición en el ranking, nombre y puntuación promedio.  

#### Etapas desarrolladas:

1. **Definición del problema:**  
   Se planteó la creación de una empresa ficticia llamada **Anime Data Studio**, dedicada al análisis y gestión de información relacionada con la industria del anime, utilizando herramientas de Big Data para optimizar la toma de decisiones.

2. **Carga y procesamiento de datos:**  
   El dataset fue descargado mediante la librería `kagglehub` y cargado en un **DataFrame de PySpark**, lo que permitió manejar los datos de forma distribuida y eficiente.  
   Posteriormente, se creó una tabla llamada **`top_anime`**, donde se almacenaron los registros para ejecutar consultas SQL dentro del entorno Databricks.

3. **Modelo Entidad–Relación (ERD):**  
   Se diseñó un modelo que representa la estructura lógica de los datos y las relaciones entre las entidades principales del sistema, facilitando su comprensión y organización.

4. **Ejecución de consultas SQL:**  
   Se realizaron operaciones de creación (`CREATE TABLE`), inserción (`INSERT INTO`), descripción (`DESCRIBE TABLE`) y exploración (`SELECT * LIMIT 5`) para verificar la estructura y contenido de la tabla.  
   Además, se aplicaron filtros con sentencias `WHERE` para obtener resultados específicos, como los animes con puntuaciones superiores a 9.0.

5. **Interpretación de resultados:**  
   Después de cada consulta, se agregó una breve interpretación que explica la finalidad de la operación y los resultados obtenidos.

#### Conclusión:
El uso de **Databricks y PySpark** permitió comprender de manera práctica cómo se gestionan y procesan los datos en entornos de **Big Data**, facilitando la manipulación, almacenamiento y análisis eficiente de información a gran escala.

