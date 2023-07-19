# PI02_Enmanuel_Aldave

# Título y Descripción: Analisis de la conectividad a internet en Argentina
En el siguiente proyecto presentare un analisis sobre los componentes mas importantes para la coneccion a internet en Argentina.
Considerando variables como: provincias, cantidad de conecciones, tipo de conectividad, velocidad.
En primer lugar, decidi comenzar trabajando con la base de datos AccesoaInternetFijoporrangosdevelocidaddebajadayprovincia_2750261689656003428.csv. Que contiene la cantidad de conecciones por velocidad, provinvia, localidad y partido. Debido a que la base de datos tenia muchas columnas decidi resumirlas en provincias, localidad, partido, velocidad promedio. EL nuevo archivo es "VelBajadaPromProv" y estara en este repositorio.
En segundo lugar, trabaje con la base de datos que representa el tipo de conectividad por provincias. El archivo es Listadodelocalidadesconconectividadainternet_2750221689656151326 para este archivo remplace los "SI" por unos y los "--" por ceros para ahcer mas facil la visualizacion de data.
Los demas archivos descargados de la pagina web los pude trabajar directamente con Power BI.
En este repositorio tambien publicare el archivo "WBSCRPING.ipynb" en el cual hice todos estos pasos y demas calculos.

# Dashboard:
Para mi dashboard decidi divir la informacion en 2 segmentos importantes: El primero fue la poblacion, ya que considero que entender el comportamiento de la poblacion con la coneccion a internet es muy importante. En este ubique en un mapa de calor las provincias con mayor promedio de velocidad de internet. Tambien explique la distribucion porcentual de los tipos de conectividad. Distribui en un mapa de dispersion la velocidad de las localidades, partidos y provincias. Grafique el crecimiento anual del promedio de accesos por cada 100 hogares. En el segundo quise plasmar el tipo de conectivdad en argentina, de esta forma analizar de manera numerica y con un vistaso general el comportamiento como pais. Grafique el crecimiento de ingresos por año y trimestr. Grafique el crecimiento por tipo de conectividad a traves de los años. La cantidad de conecciones por provincia y tipo de conectividad.

Primer Dashboard
![Primer Dashboard](https://github.com/paoloen/PI02_Enmanuel_Aldave/blob/main/db1.png)
Segundo Dashboard
![Segundo Dashboard](https://github.com/paoloen/PI02_Enmanuel_Aldave/blob/main/db2.png)

# Analisis
En primer lugar, se extrae del dashboard que mas del 50% de proincias tienen una velocidad de descarga inferior al promedio. Esto es un problema que implica a gran parte de la poblacion y es necesario comenzar un plan de accion.
En segundo lugar, analizando el promedio de conectividad por cada 100 hogares, este no guarda relacion con la velocidad de descarga que sigue siendo inferior al promedio. Es decir, hay mas hogares con coneccion en el 2022 pero con una velocidad minima.
En tercer lugar, como se puede observar en el mapa de dispercion el promedio de velocidad de descarga oscila entre los 10, 20 y 30 Mbps. Estas cifras son preocupantes para la capacidad internacional en el 2022.
En cuarto lugar, como se puede observar en el grafico de tipo de conectividad a raves de los años, la coneccion de Cable modem es la que ha crecido con mucha superioridad a comparacion de las demas. El problema con esto es que la tendencia internacional es utilizar la fibra optica, la cual ha tenido un pequeño incremento el el ultimo año pero no muy significativo.
En conclision, hablando en terminos generales la conectividad ha crecido en argentina pero la velocidad sigue siendo un problema muy grave para la mayoria de provincias.

# KPIs
# 1. Promedio de velocidad de descarga por provincia:
Este kpi permite evaluar si el promedio de velocidad de cada provincia alcanza el promedio nacional que es 28.11 Mbps.
![kpi](https://github.com/paoloen/PI02_Enmanuel_Aldave/blob/main/kp1.png)
# 2. Conectividad por cada 100 hogares por provincia:
El kpi mide si las provincias alcanzan el promedio general del 2022 que es 67.42 por cada 100 hogares.
![kpi](https://github.com/paoloen/PI02_Enmanuel_Aldave/blob/main/kp2.png)

# 3. Porcentaje representativo por tipo de conectividad:
Este kpi analiza si el tipo de conectividad supera el 10% con respecto a la poblacion en general
![kpi](https://github.com/paoloen/PI02_Enmanuel_Aldave/blob/main/kp3.png)

