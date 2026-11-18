#Objetivo del proyecto
Analizar el comportamiento de los usuarios de ConnectaTel, empresa de telecomunicaciones para identificar segmentos valiosos y patrones de uso en servicios móviles.

##Datasets utilizados

Se trabajaron con 3 fuentes de datosÑ
- Plans.csv: Que contiene los planes actuales)precio, minutos incluidos, GB incluidos, costo por extra.
- Users_latam.csv: Contiene la informacón de clientes: edad, ciudad, fecha de registro, plan contratado.
- Usage.csv: Contiene el detalle de uso real: llamadas (duración) y mensajes (longitud).

El dataser final user_profile.csv, contiene el usuario _id, nombre y apellido, edad, ciudad, registro de fecha, el plan, cantidad de llamadas, cantidad de mensajes, cantidad de minutos por llamada, el grupo de uso y el grupo etario de cada usuario registrado en la base de datos de ConnectaTel.

#Etapas del análisis 

Como analista de datos, evalué el comportamiento de los clientes de ConnectaTel una empresa de telecomunicaciones en Latinoamérica. A continuación los pasos ejecutados:

## Cargar y explorar
### Se cargaron los datos para visualizarlos correctamente y explorar la es estructuras de cada dataset.
## Identificación de problemas
### Se analizó la detección de valores nulos, valores invalidos y sentinels que pueden afectar el analisis en general y la revisión de estandarización de fechas que se encuentren fuera de rango.
## Limpieza básica de datos
### Se realizó la limpieza de datos corrigiendo sentinels
## Estadísticas por uso de cada usuario encontrado
## Visualización de distribuciones
### En este paso muy importante fue entender visualmente el comportamiento de las variables clave como uso de los servicios que ofrece la empresa a los usuarios.
### Identificación de valores atípicos (outliers) en boxplots para entender si afectaban el análisis y poder dar una respectiva limpieza o manejo de información.
## Segmentación de clientes.
### Clasificar cada usuario por categoría según su grupo de uso (Alto, Medio, Bajo).
### Clasificar cada usuario según su edad (Adulto, Adulto mayor, Joven).
## Visualización de los segmentos.
### Conocer la distribución de forma visual más clara de los segmentos anteriores como edad y uso por usurio con el servidor.
## Insigts 
### Hallazgos importantes encontrados en el análisis accionables para la empresa.

# Guía de reproducción

1. Instalar las librerías necesarias como:
   - Pandas
   - Seaborn
   - Matplotlib.pyplot
   - Numpy
2. Colocar los archivos de datos en la carpeta `/datasets/`:
   - /datasets/plans.csv
   - /datasets/users_latam.csv
   - /datasets/usage.csv
3. Abrir el notebook, ejecutar las celdas

