# Proyecto Individual 02: Telecomunicaciones: Internet
### Tabla de contenidos

1. [Contexto](#contexto)
2. [Instalacion y requisitos](#instalacion-y-requisitos)
3. [Etl y carga de datos](#etl-y-carga-de-datos)
4. [Eda](#eda)
5. [Documentos del proyecto](#documentos-del-proyecto)
6. [Datos y Fuentes](#datos-y-fuentes)
7. [Autor](#autor)

### Contexto
En este contexto, una empresa prestadora de servicios de telecomunicaciones le encarga a usted la realización de un análisis completo que permita reconocer el comportamiento de este sector a nivel nacional. Considere que la principal actividad de la empresa es brindar acceso a internet, pero también es importante considerar el comportamiento asociado al resto de los servicios de comunicación, con el fin de orientar a la empresa en brindar una buena calidad de sus servicios, identificar oportunidades de crecimiento y poder plantear soluciones personalizadas a sus posibles clientes.

### Instalacion y requisitos

- python 3.11 o superior
- pandas
- numpy
- matplotlib
- seaborn

### Etl y carga de datos:
Se procedieron a cargar las siguientes tablas:
1. Acc_vel_loc_sinrangos
2. Velocidad_sin_rangos
6. Totales Accesos por Tecnología
8. Dial-BAf
11. Penetración-hogares:
15. Ingresos

- Se realizaron procesos de transformacion en los datos, y normalizacion de variables como nombres de las columnas(necesario para la ingesta de sql server) y nombre de las tablas.
- Luego se procedio a crear las estructuras de las consultas a sql server mediante python.
- Creacion de la coneccion desde python a sql server para luego leer los datos desde power bi a sql server.
- Insertacion de los datos en sql server a partir de un dataframe de pandas.


### EDA
En el analisis exploratorio de los datos se observo que:
- la demanda de acceso a internet en Argentina está en constante crecimiento, especialmente en las categorías de mayores velocidades.
- La empresa tiene una oportunidad para seguir creciendo si se enfoca en ofrecer planes de internet con mayor velocidad y expandir su cobertura a zonas donde aún no tiene presencia.
- Es importante monitorear las tendencias del mercado y adaptar la oferta a las necesidades de los clientes para mantener una posición competitiva.
- La demanda de acceso a internet en Argentina sigue en aumento, especialmente en las categorías de mayores velocidades. La empresa tiene una gran oportunidad de crecimiento si se enfoca en ofrecer planes de internet de alta velocidad y expande su cobertura a áreas no atendidas. 

### Documentos del proyecto
- data_pi02/: Contiene los datasets del proyecto.
- EDA.ipynb: Contiene el analisis exploratorio de los datos
- Etl_carga_datos: Contiene todos los pasos de etl y la ingesta a la base de datos.
- README.md: Documentacion del proyecto

### Datos y fuentes

Los datos fueron extraidos del ente "enacom".

### Autor:

Este proyecto fue realizado por Pablo Chamena. Dataft23 grupo 03

- Linkedin: (www.linkedin.com/in/pablo-chamena-8814bb211)
