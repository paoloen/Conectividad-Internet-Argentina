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
https://github.com/paoloen/PI02_Enmanuel_Aldave/blob/main/db2.png
