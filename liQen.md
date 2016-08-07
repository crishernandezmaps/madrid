# liQen
liQen es un sistema para la creación de datos públicos abiertos desde la ciudadanía, que nace con el fin de hacer que los habitantes de cualquier ciudad del mundo pueda cooperar y colaborar en la creación de datos abiertos, promoviendo la búsqueda de soluciones a problemáticas diversas, a través del uso de aquellos datos.

liQen es una red descentralizada de producción de datos que se comunica con los datos abiertos creados gobiernos locales, nutriéndo dichos datos en un proceso que permite no duplicar esfuerzos en la creación de datos, permitiéndo el registro de versiones de conjuntos de datos, evitando su duplicidad.

## Bases de Datos Centralizadas producidas de forma distribuida
La duplicidad de los esfuerzos ciudadanos en la producción de datos nace desde el desconocimiento actual en el que nos encontramos como ciudadanos y usuarios de datos abiertos. Esto ya que meramente como consumidores de datos no es posible hoy en día saber si con anterioridad otro ciudadano ha descargado los datos que son de mi interés, y si es que ha aportado nuevos datos. Si tuviera la capacidad de conocer las distintas versiones de los conjuntos de datos abiertos, podría evitar duplicar mis esfuerzos por la búsqueda de nuevos datos, comparar versiones de conjuntos de datos, y cooperar en crear (actualizar) conjuntos de datos a nuevas versiones. 

Hoy en día a través del proceso de compresión de datos llamado 'deduplication', es posible que una vez que deseo aportar nuevos datos a un conjunto de datos, no se dupliquen y se guarden solamente los datos que son considerados como 'nuevos datos', permitiendo tener un control de las versiones de datos en el tiempo. Como ejemplo se podría tener un conjunto de datos ambientales como la contaminación acústica para tres ciudades en el mundo. Dicho conjunto de datos se guarda en un único conjunto de datos. Digamos que un grupo de ciudadanos desea aportar nuevos datos porque han realizado nuevas mediciones en alguna de éstas tres ciudades. A través del algoritmo que permite el deduplication, cuando el grupo de ciudadanos agegue dichos datos, el conjunto único de los datos de las tres ciudades, aceptará solamente aquellos que sean considerados como nuevos datos, manteniendo los que anteriormente fueron agregados. De esta forma tenemos dos versiones del conjunto de datos sobre contaminación acústica (V1 y V2), los cuales representan dos momentos de la contaminación acústica en éstas tres ciudades. 

El evitar el duplicado de datos nos entrega la posibilidad de cooperar en la creación de datos con un formato único (estándar), y que permite hacer comparaciones (entre ciudades, en el tiempo, etc.), además que nos permite poner el foco en el proceso de recolección de datos desde diversos dispositivos.

De esta forma se potencia la producción distribuída de datos entre los ciudadanos, los que al tener un formato único y un sistema inteligente que evita el duplicar datos, pueden tranquilamente centrar sus esfuerzos en crear mecanismos sociales para incentivar a que se produzcan más datos, entendiéndolos como un insumo vital de participación y creación ciudadana. 

## Cómo funciona

liQen funciona bajo tres pilares fundamentales:

### 1.- liQen Mirror
liQen funciona como facilitador de espejos o mirrors de datos públicos, es decir, mantiene una copia de los conjuntos de datos de interés provenientes desde sitios de datos abiertos gubernamentales. Junto con esto, posibilita el darle un formato único a los conjuntos de datos, homologándo datos provenientes desde diversas ciudades en el mundo. De esta forma un ciudadano desde cualquier parte del mundo puede descargar datos, por ejemplo sobre medio ambiente, en un formato único para diversas ciudades en el mundo.

### 2.- liQen Version Control
liQen promueve no solo el descargar datos, sino que su uso activo y **devolución**. Por devolución se comprende el proceso en el cual un ciudadano o grupo de ciudadanos deciden que deben retribuir a liQen entregando nuevos datos que recolecten en su ciudad. 

Para facilitar ese proceso liQen utiliza el sistema [Dat](http://dat-data.com/), el cual favorece la comunicación de datos evitando la duplicidad de los mismos. De esta forma se agregan datos desde diversas fuentes a la versión central que mantiene liQen del conjunto general de datos. Como ejemplo, luego una persona desde cualquier parte del mundo puede conocer cuál es la versión actual de datos abiertos sobre medio ambiente en las ciudades agregadas a liQen.

### 3.- liQen Merge
liQen está en constante conversación con los gobiernos locales de diversas ciudades en el mundo, ya que no desea competir con ellos en la creación de datos, sino que aportar y contribuir a tener más y mejores datos en la ciudad, rescatando todos los esfuerzos ciudadanos en la producción de datos. Por esta razón liQen propone un *merge* a los gobiernos locales.

Un merge es entendido en este contexto como la combinación de bases de datos, mezclando los datos producidos por los gobiernos locales y los datos producidos por la ciudadanía, haciendo convivir un nuevo repositorio de datos ´híbrido', de aportes gubernamentales y ciudadanos.

## Prototipo Ambiental
Se propone la creación de un prototipo en el cual se recorra todo el proceso aquí propuesto, tomando los datos ambientales (o incluso un sub-conjunto de datos, como la contaminación acústica), para tres ciudades: Madrid, Santiago y Londres; con el fin de crear la versión número 1 de datos de contaminación para éstas tres ciudades (liQen datos ambientales V.0.1 o LAM V.0.1).

**NOTA**: LAM = liQen Ambiental.

Dichos datos deben ser procesados para llegar a un estándar común, los cuales serán dispuestos en Internet para su descarga por tres personas o grupos de personas en éstas tres ciudades. 

Las personas o grupos de personas en éstas ciudades agregarán nuevos datos y los enviarán a liQen utilizando el sistema 'dat', antes mencionado, respetando el formato de los datos. Una vez que se reciban los datos, se agregarán a la primera base de datos creada por el equipo liQen, generando la versión LAM V.0.2
de liQen datos ambientales. 

Finalmente en el sitio de liQen estarán dispuestas las dos versiones de datos ambientales (LAM V.0.1 y LAM V.0.2), las cuales pueden ser descargadas nuevamente por cualquier persona de forma abierta. 

## Beneficios 
La creación de liQen permitirá que los usuarios sean parte activa de la creación de datos en la ciudad. Por otro lado, en ciudades más avanzadas en estos temas, permitirá que los datos no se dupliquen, y por otro lado, permitirá que los ciudadanos conozcan los esfuerzos que otros ciudadanos están llevando adelante en la producción y apertura de datos. 

liQen utiliza la tecnología de comunicación de datos "Dat", reservada hasta hoy para el compartir grandes bases de datos científicas, es decir, es la primera experiencia en la que se prueban estándares científicos de compartir datos para datos abiertos gubernamentales y ciudadanos. 

Finalmente, liQen se transformaría en el primer lugar en aglutinar datos abiertos de forma centralizada, es decir, que se aglutina en un solo sitio datos abiertos provenientes desde diversas ciudades en el mundo. 

## Posibilidades

### Software 
Utilizando modelos como el de Github y Node.js para la creación colaborativa de software y la instalación de paquetes de código, es posible agregar la capa de análisis a los datos, es decir, crear código específico para el análisis de datos abiertos desde liQen. 

### Herramientas para la recolección de datos
Es posible crear aplicaciones móviles, sensores que potencien los móviles (mirar [Lab4U](http://ingenieria.uchile.cl/noticias/106153/lab4u-la-innovacion-que-permite-llevar-un-laboratorio-en-el-bolsillo) y [Ara Project](https://atap.google.com/ara/)) o algoritmos para el procesamiento de datos recopilados desde smartphones, basados en la filosofía de liQen, que es la colaboración en la creación de datos, no-duplicidad y merge. 

### Feed de Visualizaciones
Visualizaciones períodicas que muestren y comparen (liQen por defecto permite la comparación), entre ciudades basados en variables diversas. Por ejemplo: visualizaciones colgadas en Internet que muestren el estado de la contaminación acústica en diversas ciudades del mundo, de acuerdo a la última versión de datos sobre ese tema en liQen, con el fin de difundir los descubrimientos hechos por los ciudadanos en el mundo, posibilitados por nuestra plataforma. 
 


