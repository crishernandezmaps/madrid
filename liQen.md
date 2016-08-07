# liQen
liQen es un sistema para la creaci�n de datos p�blicos abiertos desde la ciudadan�a, que nace con el fin de hacer que los habitantes de cualquier ciudad del mundo pueda cooperar y colaborar en la creaci�n de datos abiertos, promoviendo la b�squeda de soluciones a problem�ticas diversas, a trav�s del uso de aquellos datos.

liQen es una red descentralizada de producci�n de datos que se comunica con los datos abiertos creados gobiernos locales, nutri�ndo dichos datos en un proceso que permite no duplicar esfuerzos en la creaci�n de datos, permiti�ndo el registro de versiones de conjuntos de datos, evitando su duplicidad.

## Bases de Datos Centralizadas producidas de forma distribuida
La duplicidad de los esfuerzos ciudadanos en la producci�n de datos nace desde el desconocimiento actual en el que nos encontramos como ciudadanos y usuarios de datos abiertos. Esto ya que meramente como consumidores de datos no es posible hoy en d�a saber si con anterioridad otro ciudadano ha descargado los datos que son de mi inter�s, y si es que ha aportado nuevos datos. Si tuviera la capacidad de conocer las distintas versiones de los conjuntos de datos abiertos, podr�a evitar duplicar mis esfuerzos por la b�squeda de nuevos datos, comparar versiones de conjuntos de datos, y cooperar en crear (actualizar) conjuntos de datos a nuevas versiones. 

Hoy en d�a a trav�s del proceso de compresi�n de datos llamado 'deduplication', es posible que una vez que deseo aportar nuevos datos a un conjunto de datos, no se dupliquen y se guarden solamente los datos que son considerados como 'nuevos datos', permitiendo tener un control de las versiones de datos en el tiempo. Como ejemplo se podr�a tener un conjunto de datos ambientales como la contaminaci�n ac�stica para tres ciudades en el mundo. Dicho conjunto de datos se guarda en un �nico conjunto de datos. Digamos que un grupo de ciudadanos desea aportar nuevos datos porque han realizado nuevas mediciones en alguna de �stas tres ciudades. A trav�s del algoritmo que permite el deduplication, cuando el grupo de ciudadanos agegue dichos datos, el conjunto �nico de los datos de las tres ciudades, aceptar� solamente aquellos que sean considerados como nuevos datos, manteniendo los que anteriormente fueron agregados. De esta forma tenemos dos versiones del conjunto de datos sobre contaminaci�n ac�stica (V1 y V2), los cuales representan dos momentos de la contaminaci�n ac�stica en �stas tres ciudades. 

El evitar el duplicado de datos nos entrega la posibilidad de cooperar en la creaci�n de datos con un formato �nico (est�ndar), y que permite hacer comparaciones (entre ciudades, en el tiempo, etc.), adem�s que nos permite poner el foco en el proceso de recolecci�n de datos desde diversos dispositivos.

De esta forma se potencia la producci�n distribu�da de datos entre los ciudadanos, los que al tener un formato �nico y un sistema inteligente que evita el duplicar datos, pueden tranquilamente centrar sus esfuerzos en crear mecanismos sociales para incentivar a que se produzcan m�s datos, entendi�ndolos como un insumo vital de participaci�n y creaci�n ciudadana. 

## C�mo funciona

liQen funciona bajo tres pilares fundamentales:

### 1.- liQen Mirror
liQen funciona como facilitador de espejos o mirrors de datos p�blicos, es decir, mantiene una copia de los conjuntos de datos de inter�s provenientes desde sitios de datos abiertos gubernamentales. Junto con esto, posibilita el darle un formato �nico a los conjuntos de datos, homolog�ndo datos provenientes desde diversas ciudades en el mundo. De esta forma un ciudadano desde cualquier parte del mundo puede descargar datos, por ejemplo sobre medio ambiente, en un formato �nico para diversas ciudades en el mundo.

### 2.- liQen Version Control
liQen promueve no solo el descargar datos, sino que su uso activo y **devoluci�n**. Por devoluci�n se comprende el proceso en el cual un ciudadano o grupo de ciudadanos deciden que deben retribuir a liQen entregando nuevos datos que recolecten en su ciudad. 

Para facilitar ese proceso liQen utiliza el sistema [Dat](http://dat-data.com/), el cual favorece la comunicaci�n de datos evitando la duplicidad de los mismos. De esta forma se agregan datos desde diversas fuentes a la versi�n central que mantiene liQen del conjunto general de datos. Como ejemplo, luego una persona desde cualquier parte del mundo puede conocer cu�l es la versi�n actual de datos abiertos sobre medio ambiente en las ciudades agregadas a liQen.

### 3.- liQen Merge
liQen est� en constante conversaci�n con los gobiernos locales de diversas ciudades en el mundo, ya que no desea competir con ellos en la creaci�n de datos, sino que aportar y contribuir a tener m�s y mejores datos en la ciudad, rescatando todos los esfuerzos ciudadanos en la producci�n de datos. Por esta raz�n liQen propone un *merge* a los gobiernos locales.

Un merge es entendido en este contexto como la combinaci�n de bases de datos, mezclando los datos producidos por los gobiernos locales y los datos producidos por la ciudadan�a, haciendo convivir un nuevo repositorio de datos �h�brido', de aportes gubernamentales y ciudadanos.

## Prototipo Ambiental
Se propone la creaci�n de un prototipo en el cual se recorra todo el proceso aqu� propuesto, tomando los datos ambientales (o incluso un sub-conjunto de datos, como la contaminaci�n ac�stica), para tres ciudades: Madrid, Santiago y Londres; con el fin de crear la versi�n n�mero 1 de datos de contaminaci�n para �stas tres ciudades (liQen datos ambientales V.0.1 o LAM V.0.1).

**NOTA**: LAM = liQen Ambiental.

Dichos datos deben ser procesados para llegar a un est�ndar com�n, los cuales ser�n dispuestos en Internet para su descarga por tres personas o grupos de personas en �stas tres ciudades. 

Las personas o grupos de personas en �stas ciudades agregar�n nuevos datos y los enviar�n a liQen utilizando el sistema 'dat', antes mencionado, respetando el formato de los datos. Una vez que se reciban los datos, se agregar�n a la primera base de datos creada por el equipo liQen, generando la versi�n LAM V.0.2
de liQen datos ambientales. 

Finalmente en el sitio de liQen estar�n dispuestas las dos versiones de datos ambientales (LAM V.0.1 y LAM V.0.2), las cuales pueden ser descargadas nuevamente por cualquier persona de forma abierta. 

## Beneficios 
La creaci�n de liQen permitir� que los usuarios sean parte activa de la creaci�n de datos en la ciudad. Por otro lado, en ciudades m�s avanzadas en estos temas, permitir� que los datos no se dupliquen, y por otro lado, permitir� que los ciudadanos conozcan los esfuerzos que otros ciudadanos est�n llevando adelante en la producci�n y apertura de datos. 

liQen utiliza la tecnolog�a de comunicaci�n de datos "Dat", reservada hasta hoy para el compartir grandes bases de datos cient�ficas, es decir, es la primera experiencia en la que se prueban est�ndares cient�ficos de compartir datos para datos abiertos gubernamentales y ciudadanos. 

Finalmente, liQen se transformar�a en el primer lugar en aglutinar datos abiertos de forma centralizada, es decir, que se aglutina en un solo sitio datos abiertos provenientes desde diversas ciudades en el mundo. 

## Posibilidades

### Software 
Utilizando modelos como el de Github y Node.js para la creaci�n colaborativa de software y la instalaci�n de paquetes de c�digo, es posible agregar la capa de an�lisis a los datos, es decir, crear c�digo espec�fico para el an�lisis de datos abiertos desde liQen. 

### Herramientas para la recolecci�n de datos
Es posible crear aplicaciones m�viles, sensores que potencien los m�viles (mirar [Lab4U](http://ingenieria.uchile.cl/noticias/106153/lab4u-la-innovacion-que-permite-llevar-un-laboratorio-en-el-bolsillo) y [Ara Project](https://atap.google.com/ara/)) o algoritmos para el procesamiento de datos recopilados desde smartphones, basados en la filosof�a de liQen, que es la colaboraci�n en la creaci�n de datos, no-duplicidad y merge. 

### Feed de Visualizaciones
Visualizaciones per�odicas que muestren y comparen (liQen por defecto permite la comparaci�n), entre ciudades basados en variables diversas. Por ejemplo: visualizaciones colgadas en Internet que muestren el estado de la contaminaci�n ac�stica en diversas ciudades del mundo, de acuerdo a la �ltima versi�n de datos sobre ese tema en liQen, con el fin de difundir los descubrimientos hechos por los ciudadanos en el mundo, posibilitados por nuestra plataforma. 
 


