
![Apache Hadoop](https://img.shields.io/badge/Apache%20Hadoop-66CCFF?style=for-the-badge&logo=apachehadoop&logoColor=black)
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-FDEE21?style=flat-square&logo=apachespark&logoColor=black)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-000?style=for-the-badge&logo=apachekafka)

# Actividades - Big Data


## Actividad 1: 
Interactuar desde la linea de comandos con SQOOP, con la BBDD, y realizar consultas a los datos e ingesta de en HDFS.


* 📄 **Notebook:** Sqoop_Hdfs.ipynb

1) SQOOP: ingesta de datos
2) Sistema de ficheros HDFS: configuración del entorno.


## Actividad 2: 
Aplicacion de Algortimos de Machine Learning en Spark.

* 📄 **Notebook:** Machine Learning_spark.ipynb

1) Carga de datos y seleccion de variables.
2) Analisis descriptivo y limpieza de datos.
3) Análisis visual.
4) Regresión logistica.
5) Arbol de decisión. 


## Actividad 3: 
Extracción de conocimiento de fuentes de datos heterogéneas mediante Spark SQL, RDDs

* 📄**Notebook:** Dataframes_IMDB.ipynb

1) Inicialización del entorno y carga de archivos.
    * 1.1 Carga de archivos en HDFS
    * 1.2 Carga de los archivos en Spark y exploración
    * 1.3 Particionado

2) Análisis de los datos
   * 2.1 Consultas mediante sql
   * 2.2 Analizando el dataset con Spark SQL

   * 2.2.1 ¿Cuál es el usuario que ha escrito más reviews? ¿Y el que ha escrito menos (en caso de que haya más de uno indica cuántos hay)?

   * 2.2.2 ¿Cuál es el usuario que ha escrito más reviews con spoiler?

   * 2.2.3 ¿Existe alguna inconsistencia entre los ratings del archivo de detalles y el archivo de reviews?

   * 2.2.4 De las películas de Acción, ¿cuál es la relación entre el número de spoilers respecto al total?

   * 2.2.5 ¿Cuál es la media de antigüedad de las películas? ¿Y cuál es la diferencia (en número absoluto) media de la antigüedad de las películas de acción y las de terror (Horror)?

   * 2.2.6 ¿Cuál es el usuario que pone mejores valoraciones (media aritmética)? ¿Y el que las pone peores? NOTA: Ignoraremos a los usuarios que han escrito menos de 10 reviews y si hay más de uno, muéstralos todos.

   * 2.2.7 Mostrad la media de los rating de las películas por género.


## Actividad 4: 
Contando palabras: Construye una aplicación que cuente palabras de forma eficiente.

* 📄**Notebook:** WordCount.ipynb

1) Creación de un RDD y un pair RDD.
2) Contar palabras usando un pair RDD.
3) Encontrar las palabras individuales y su frecuencia de aparición media.
4) Aplicar las funcionalidades desarrolladas a un archivo de texto.
5) Calcular algunos estadísticos.


## Actividad 5: 
Kafka como una fuente de datos para leer y procesar mensajes en tiempo real.

* 📄**Notebook:** Kafka.ipynb

1) Creación de un topic.
2) Productor / Consumidor.
3) Particiones.
4) Offsets.
5) Adquisición de datos en tiempo real.



# Tech Stack
* Apache Spark
* PySpark
* PySpark SQL
* API SparkSQL
* SQOOP
* HDFS
* RDDs
* Kafka
