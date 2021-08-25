# Econometría
Se considera que, desde el punto de vista tradicional la teoría económica postula un modelo y la econometría se ocupa de contrastar esa teoría o de medir relaciones entre variables económicas, sin embargo, a veces la teoría no proporcionaun modelo explícito y hay que especificarlo,  ahora bien, desde una razón "moderna" la econometría está interesada en usar datos para entender mejor un fenómenos de interés, intentando encontrar un modelo que sea capaz de explicarlas principales características de los datos.

Hay una tipología de datos que rige la econometría, entre ellos están los siguientes:
- **Series temporales:** miden una variable determinada durante período de tiempos sucesivos, ejemplo: PIB de un país
- **Sección cruzada**: miden el valor de una variable en un momento dado del tiempo para distintas entidades, ejemplos: activos en una cartera de inversión 
- **Datos panel:** miden el valor de una variable determinada para distintas entidades a lo largo del tiempo, eje: PIB + PIB per cápita, Inflación de un grupo de países a los largo de un período de 10 años.

Inicialmente, hay diferentes procesos de modelización, para este caso se expondrán los métodosque estudian la relación lineal existente entre dos o más variables de manera experimental.

Considerando lo expuesto anteriormente, este repositorio se centrará en mostrar algunos modelos empíricos  de regresiones lineales simples y múltiples para contrastar con algún tipo de teoría

## Excel "ntmrl"
En el documento de excel llamado **ntmrl**, se encuentra una base de datos la cual se compone de 5 columnas diferentes en las cuales se encuentran datos referentes a:
- _Columna 1_: Fecha (Enero de 2009 - Diciembre 2019)
- _Columna 2:_ Exportaciones (Millones de dólares FOB)
- _Columna 3:_ Importaciones (Millones de dólares FOB)
- _Columna 4:_ TRM (Tasa representativa del mercado, COP/USD)
- _Columna 5:_ Balanza Comercial (Exportaciones - Importaciones) 

## R "EconometriaS1"

En este documento de R Studio, se desarrollaran distintos calculos orientados a entender de una manera clara como elaborar e interpretar un modelo de regresion lineal simple y un modelo de regresion lineal multiple, esto se desarrolló en base a la base de datos de Excel mencionada anteriormente. En este archivo, los temas tratados son los señalados a continuación:
- Importacion y definición de variables a partir de un archivo en externo a R Studio (Excel)
- Creación de resumenes estadísticos
- Estimación de modelos de regresión lineal simple y multiple
- Gráficos de residuos
- Pruebas estadisticas de linealidad
- Pruebas estadísticas de normalidad
- Pruebas estadísticas de homocedasticidad
- Multicolinealidad
