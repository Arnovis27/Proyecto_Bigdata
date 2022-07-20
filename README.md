# Proyecto Big data
El proyecto se realio usando la tecnologia de python consumiendo la APi de twitter y mineria de datos para extraer informacion referente a las conversaciones que tenian los usuarios de twitter en base a la palabra covif-19, con el fin de obtener el uso de las palabras mas frecuentes asi mismo como otros factores del lenguaje

## Funcionalidades
**Funcionalidad 1:** Recolectar informacion de twitter referente a un hashtag definido  
**Funcionalidad 2:** Delimitar la region de obtencion de informacion a Colombia  
**Funcionalidad 3:** Normalizar los datos  
**Funcionalidad 4:** Separar las palabras de cada publicacion  
**Funcionalidad 5:** Estimar la frecuencia de cada palabra  
**Funcionalidad 6:** Realizar analisis respectivos con la informacion (partes del lenguajes, TF-IDF, etc)

## Instalación
Se puede instalar clonando el repositorio con ```git clone url```

## Como se usa
Para iniciar el programa deberas tener los datos de la API de twitter y colocarlos en las casillas correspondientes en el Jupyter notebook, luego puedes correr la aplicacion normalmente ejecutandola en RUN

### Manejo de datos
Usando un archivo csv se guardaron las publicaciones referentes a los ultimos 7 dias segun las restricciones que producia la Api de twitter, asi mismo para obtener el menor uso posible de memoria se decidio almacenar cada pulicacion en el archivo debido a que eran demasiados.

### Analisis
Se generaron datos para analizar mejor el comportamiento de esta informacion como serian: Tweets por dia, Extraccion de palabras y la frecuencia de estas mismas, Extraccion de partes del lenguaje (Verbos, Sustantivos, Adjetivos, etc), TF-IDF, toda la informacion esta proporcionada visualmente dentro del archivo pandas [proyectobigdata.ipynb](proyectobigdata.ipynb)

## Estado del proyecto
El proyecto se encuentra terminado
