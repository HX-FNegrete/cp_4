<h1>Bootcamp Módulo 4</h1>
<p><img alt="henry" src="henry.jpeg" /> </p>
<h2>Elegir la opción correspondiente</h2>
<p> 1) La <code>tolerancia a particiones</code> es un concepto relacionado con: </p>
<p>Opciones: </p>
<p>a- Las particiones lógicas en los discos duros del cluster   
  
b- Que se puedan utilizar particiones en lugar de índices para las tablas   
  
c- Que el sistema disponibiliza información aún habiendo tenido fallas de red  
  
d- Que el sistema pueda gestionar particiones lógicas en los discos duros  
  
e- Que la administracion del sistema esté particionada </p>  

<p>2) El concepto de <code>escalabilidad horizontal</code>: </p>
<p>Opciones: </p>
<p>a- Consiste en un conjunto de equipos que trabajan como un todo respecto al procesamiento y almacenamiento de los datos  
  
b- Es una arquitectura cliente-servidor adaptada a la gestión de grandes volúmenes de datos, pero replicado en varios servidores  
  
c- Es un esquema de servicios  
  
d- Es una arquitectura cliente-servidor adaptada a la gestión de grandes volúmenes de datos  
  
e- Funciona sobre cualquier sistema operativo </p>  

<p>3) En Big Data, la característica <code>variedad</code> consiste en: </p>
<p>Opciones: </p>
<p>a- El establecimiento de un flujo de datos masivo y continuo  
  
b- Poder gestionar y canalizar grandes volúmenes de datos  
  
c- Poder trabajar con datos estructurados y no estructurados </p>  

<p>4) ¿Cuáles son las características fundamentales de los motores de bases de datos No-SQL? </p>  

<p>Opciones: </p>
<p>a- Consistencia eventual, aislamiento y durabilidad  
  
b- Uso de particiones, escalabilidad horizontal y casos de uso específicos  
  
c- Tolerancia a particiones, escalabilidad horizontal y casos de uso específicos  
  
d- Tolerancia a particiones, consistencia horizontal y casos de uso de negocio </p>  

<p>5) El Teorema CAP dice que: </p>
<p>Opciones: </p>
<p>a- Un sistema SQL tiene la característica de ser consistente  
  
b- Un sistema No-SQL puede ser tolerante a particiones y consistente  
  
c- No es posible para ningún sistema de bases de datos garantizar al mismo tiempo consistencia, disponibilidad y tolerancia a particiones   
  
d- Un sistema SQL puede ser consistente y estar disponible  
  
e- Un sistema SQL o No-SQL no puede garantizar al mismo tiempo consistencia, disponibilidad y tolerancia a particiones </p>  

<p>6) Si se piensa en montar un Data Warehouse sobre Hadoop: </p>
<p>Opciones: </p>
<p>a- Sólo sería factible implementar un DataLake  
  
b- Hive es una opción, dado que es una herramienta que asigna una estructura tabular a los datos en bruto almacenados en HDFS  
  
c- Es posible, pero sólo se pueden utilizar motores de bases de datos que traten con datos no estructurados  
  
d- Solo es posible utilizar motores de bases de datos No-SQL </p>  

<p>7) Respecto al Data Lake, ¿cuál de las siguientes afirmaciones es correcta?: </p>
<p>Opciones: </p>
<p>a- Es una mejora del Data Warehouse, ya que consiste en tener más capacidad de hardware para la gestión de grandes caudales de datos  
  
b- Es un repositorio unificado de datos estructurados y no estructurados que prioriza el almacenamiento de los datos en su formato original, para posteriormente ser procesados de acuerdo a la demanda  
  
c- Es un sistema de ETL distribuido </p>  

<p>8) ¿Cuál de las siguientes afirmaciones NO es correcta? </p>
<p>Opciones: </p>
<p>a- Cada DataNode tiene un sistema de archivo local al cual no puede acceder el nodo maestro.  
  
b- El NameNode tiene la tarea de balancear la carga sobre el cluster a la hora de almacenar un nuevo archivo.  
  
c- El NameNode optimiza el ancho de banda y balancea la carga de procesamiento. </p>  

<p>9) En un cluster que tiene un factor de réplica de 3 y un tamaño de bloque de 64 MB, se guarda un archivo de 6500 MB ¿Cuántos segmentos del archivo original se deberán distribuir a lo largo del cluster? </p>
<p>Opciones: </p>
<p>a- 305  
  
b- 306  
  
c- 102 </p>  

<p>10) Si se considera que una tabla dentro de Hive va a ser consultada mediante consultas de agregación (Avg(), Sum(), Max(), etc): </p>
<p>Opciones: </p>
<p>a- Conviene que esté almacenada en formato Avro  
  
b- No es Hive la herramienta adecuada, sería mejor elegir un motor No-SQL  
  
c- Conviene que esté almacenada en formato Parquet </p>  

<p>11) En caso de realizar una operación de tipo DROP TABLE en Hive: </p>
<p>Opciones: </p>
<p>a- No está habilitada tal funcionalidad  
  
b- Si la tabla es "External" se eliminan solo los datos fuente  
  
c- Si la tabla es "Managed" se elimina tanto la metadata como los datos fuente  
  
d- Si la tabla es "Managed" se elimina la metadata pero no los datos fuente </p>  

<p>12) Dentro de la arquitectura <code>docker</code> encontramos: </p>
<p>Opciones: </p>
<p>a- Contenedores, imágenes, volúmenes y redes  
  
b- Imagenes, archivos YML, herramientas de Big Data y redes  
  
c- Máquinas virtuales de poca capacidad de almacenamiento  
  
d- Contenedores, servicios, volúmenes y redes  
  
e- Contenedores y máquinas virtuales </p>  

<p>13) ¿Cuál de las siguientes afirmaciones NO es correcta? </p>
<p>Opciones: </p>
<p>a- Docker ejecuta sus procesos de forma nativa  
  
b- Los servicios de docker pueden llegar a consumir más recursos de los que se les permite  
  
c- Cada contenedor tiene un ID único y también poseen un nombre </p>  

<p>14) ¿Cuál es la estructura de datos fundamental de <code>Apache Spark</code>? </p>
<p>Opciones: </p>
<p>a- Dataset, que solo está disponible para Scala y Java  
  
b- GraphX, que permite la manipulación de datos en formato de grafos  
  
c- RDD (Resilient Distributed Dataset)  
  
d- Datasets y Dataframes  
  
5- Tablas y Grafos </p>  

<p>15) Kafka es un sistema de mensajes distribuido: </p>
<p>Opciones: </p>
<p>a- Enfocado en agilizar la comunicación entre los procesos productores y consumidores  
  
b- Que solo se puede utilizar para procesamiento streaming  
  
c- Que monitorea un proceso streaming  
  
d- Que utiliza el patrón productor-consumidor y maneja el concepto de tópico para categorizar esos mensajes </p>  

<h2>Utilizando los archivos provistos en las carpetas "data_cp_airports" y "data_cp_flights" responder:</h2>
<h3>Nota: Para la realización de los puntos 15 al 20, se puede utilizar el entorno visto en clase ubicado en el repositorio: https://github.com/soyHenry/DS-M4-Cluster_Spark</h3>
<p>16) En la carpeta "data_cp_flights" hay un archivo Parquet, comprimido con Snappy, en adelante, la tabla "flights". ¿Qué cantidad de columnas posee? </p>
<p>Opciones: </p>
<p>1- 5  
  
2- 7  
  
3- 12 </p>  

<h3>Quitar de la tabla "flights" los registros que tengan valores nulos o faltantes en los campos "ArrDelay" y "DepDelay". Luego contestar:</h3>
<p>17) ¿Cuál es la tupla de aeropuertos, con mayor cantidad de vuelos entre sí? Nota: Es posible tomar el nombre del aeropuerto desde el archivo "airports.json" ubicado en la carpeta "data_cp_airports", donde "airport_id" se puede relacionar con "OriginAirportID" y "DestAirportID" de la tabla "flights" </p>
<p>Opciones: </p>
<p>1-Honolulu International - Kahului Airport  
  
2-San Francisco International - Los Angeles International  
  
3-Los Angeles International - McCarran International </p>  

<h3>Si consideramos que cuando el campo ArrDelay es mayor a 15, el vuelo está demorado, contestar:</h3>
<p>18) ¿Cuál es el aeropuerto con el mayor promedio de demora en arribos, teniendo en cuenta el de orígen? (OriginAirport - ArrDelay) </p>
<p>Opciones: </p>
<p>1-Washington Dulles International  
  
2-Nashville International  
  
3-Chicago Midway International </p>  

<p>19) ¿Cuál es la tupla de aeropuertos, con mayor cantidad de vuelos demorados entre sí? Nota: Es posible tomar el nombre del aeropuerto desde el archivo "airports.csv", donde "airport_id" se puede relacionar con "OriginAirportID" y "DestAirportID" de la tabla "flights" </p>
<p>Opciones: </p>
<p>1-Honolulu International - Kahului Airport  
  
2-San Francisco International - Los Angeles International  
  
3-Chicago O'Hare International - San Francisco International </p>  

<p>20) ¿Cuál es la cantidad de vuelos demorados? </p>
<p>Opciones: </p>
<p>1-380502  
  
2-1255037  
  
3-2309883 </p>  

