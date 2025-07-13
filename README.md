# Examen-R-Data-Science
 video del codigo
https://drive.google.com/file/d/1e6XYRqI8mHV2K5f-6_LL6khYOSd0hHHi/view?usp=sharing


                                                       1 )INTRODUCCIÓN:
"Este proyecto se centra en el análisis exploratorio y la modelización de un conjunto de datos estructurado, importado desde un formato tabular (.xlsx). La fuente del dataset es un proveedor de servicios transitorios externo, que registra el consumo granular de horas hombre dentro de las operaciones de Carozzi Teno durante el periodo 12 meses 2024.

Los objetivos analíticos principales de este estudio son:

a) Identificación y caracterización de patrones de consumo:

b) Visualización de la frecuencia y estructura de la distribución: Se.- visualizar por frecuencia de la distribucion de horas consumidas (graficos de distrubucion aliatoria).

c)vizualizacion de las horas cosumido de por planta y Centro costo y generar presuepuento proximo año.Prediccion de necesidad de horas extras por centro costo y por planta.

1.1 CONCEPTOS DE LOS OBJETIVOS

a).-Identificación y caracterización de patrones de consumo: Mediante técnicas de visualización de datos (como histogramas y gráficos de densidad) y estadísticas descriptivas (resúmenes, medidas de tendencia central y dispersión), se buscará comprender la distribución del consumo de horas hombre a través de dimensiones operacionales clave, específicamente por planta y centro de costo. Esto implica analizar la forma de la distribución (simetría, curtosis), la densidad de los datos (concentración de valores) y la identificación de subgrupos.

b).-Visualización de la frecuencia y estructura de la distribución: Se utilizarán gráficos de distribución (como histogramas y posiblemente gráficos de cajas) para representar visualmente la frecuencia de ocurrencia de diferentes rangos de consumo de horas hombre. Además, se pueden emplear visualizaciones de distribución aleatoria como herramienta conceptual o comparativa para contrastar la distribución real de los datos con distribuciones teóricas conocidas, lo que puede ayudar a fundamentar la elección de modelos estadísticos o a entender mejor las propiedades de los datos."

c)vizualizacion de las horas cosumido de por planta y Centro costo y generar presuepuento proximo año: El código integra técnicas estadísticas (transformación logarítmica Explica cómo la transformación logarítmica (log(1 + x) cuando hay ceros puede ayudar a hacer que una distribución sea más simétrica y se aproxime a la normalidad, destacando su utilidad en modelos predictivos y análisis estadísticos. Proporciona un ejemplo aplicado a las variables 'Hrs Normal' y 'Hrs Extra', mostrando cómo realizar esta transformación. Luego, describe cómo visualizar y analizar las variables transformadas. Además, detalla el proceso para generar un presupuesto basado en el consumo histórico por Centro de Costo (Ceco) y Planta, incluyendo una proyección a 12 meses. Finalmente, explica cómo presentar esta proyección mensual en un gráfico lineal que muestre tanto las horas normales como las horas extras.

2.- PREPROCESAMIENTO DE DATOS.

2.1.- INSTALACION DE PACKAGES E IMPORTACIÓN DE DATASET DE GOOGLE DRIVE Y LIMPIEZA.


2.2.- VISUALIZACIÓN DE LA LIMPIEZA DEL ARCHIVO TEMPORAL Y ANALISIS DE CORRELACION MULTIPLE


a) Identificación y caracterización de patrones de consumo:
a).1 Distrubucion y dencidad horas de consumo.

B).- Visualización de la frecuencia y estructura de la distribución: Se.- visualizar por frecuencia de la distribucion de horas consumidas (graficos de distrubucion aliatoria)

c)vizualizacion de las horas cosumido de por planta y Centro costo y generar presuepuento proximo año con una Prediccion de necesidad de horas extras por centro costo y planta.
