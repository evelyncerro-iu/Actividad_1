### 📝 Descripción de la actividad

Esta actividad se desarrolló en el entorno **Databricks (Free Edition)**, utilizando **PySpark** como motor de procesamiento para aplicar conceptos de modelado y análisis de datos.

El objetivo principal fue aplicar los fundamentos de la analítica y del lenguaje SQL para manipular y explorar un conjunto de datos real, en este caso el **Top Anime Dataset** obtenido desde Kaggle.  
El análisis se centró en identificar los factores que influyen en la popularidad y calificación de los animes más destacados.

#### Etapas desarrolladas:
1. **Definición del problema:**  
   Se planteó la creación de la empresa ficticia **Anime Data Studio**, dedicada al análisis de datos en la industria del anime, con el propósito de identificar tendencias y patrones de éxito.

2. **Carga y preparación de los datos:**  
   El dataset fue descargado mediante la librería `kagglehub` y cargado en un DataFrame de PySpark.  
   Posteriormente se creó una tabla llamada **`top_anime`** para realizar consultas SQL directamente desde Databricks.

3. **Modelo Entidad–Relación (ERD):**  
   Se diseñó un modelo conceptual que representa las relaciones entre animes y géneros, empleando un diagrama ER para visualizar las entidades y sus vínculos.

4. **Consultas SQL y análisis:**  
   Se ejecutaron sentencias como `CREATE TABLE`, `INSERT INTO`, `DESCRIBE TABLE` y `SELECT * LIMIT 5` para comprobar la estructura y el contenido de los datos.  
   También se aplicaron filtros (`WHERE`, `ORDER BY`, `LIMIT`) para analizar animes con calificaciones superiores a 9.0 y otros criterios relevantes.

5. **Interpretación de resultados:**  
   Después de cada consulta se redactaron interpretaciones breves que explican el significado de los resultados y su relación con el objetivo analítico del proyecto.

#### Conclusión:
El uso de **Databricks** permitió integrar el modelado de datos, consultas SQL y análisis con PySpark de manera práctica y visual, fortaleciendo las competencias en procesamiento de datos masivos y análisis descriptivo.
