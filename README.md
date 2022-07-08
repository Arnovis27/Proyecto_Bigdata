# Proyecto Big data
El proyecto se realio usando la tecnologia de python consumiendo la APi de twitter y mineria de datos para extraer informacion referente a las conversaciones que tenian los usuarios de twitter en base a la palabra covif-19, con el fin de obtener el uso de las palabras mas frecuentes asi mismo como otros factores del lenguaje

## Manejo de datos
Usando un archivo csv se guardaron las publicaciones referentes a los ultimos 7 dias segun las restricciones que producia la Api de twitter, asi mismo para obtener el menor uso posible de memoria se decidio almacenar cada pulicacion en el archivo debido a que eran demasiados.

## Analisis
Se generaron datos para analizar mejor el comportamiento de esta informacion como serian: Tweets por dia, Extraccion de palabras y la frecuencia de estas mismas, Extraccion de partes del lenguaje (Verbos, Sustantivos, Adjetivos, etc), TF-IDF, toda la informacion esta proporcionada visualmente dentro del archivo pandas [proyectobigdata.ipynb](Proyecto_Bigdata/proyectobigdata.ipynb)
