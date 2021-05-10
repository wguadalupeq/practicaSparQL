# Practica sobre SparQL
Este repositorio abarca las consultas SparQL a estructuras RDF, además la de creación de esta estructura y un resumen de los pasos que realizamos para la ejecución de nuestro proyecto.

Integrantes: 

- William Guadalupe 
<<<<<<< HEAD
- Danilo Blas
=======
- Danilo Blas Salas
>>>>>>> 265d8a6d4e25e8649231eef87675aceb9c11b314
- Victor Chavez Bruno
- Bryan Asmat 

Para iniciar el presente proyecto se ha usado la base de conocimiento de la Wikidata realizando consultas online [Wikidata Query Service](https://query.wikidata.org/) con lo cual seguiremos los siguientes pasos para que se entienda como se ha creado la estructura RDF sin embargo si solo se desea esta estructura puede saltarse al paso 4.

1. Accederemos al enlace mencionado anteriormente.
2. Podemos usar las consultas con extensión `.rq` que estan almacenadas en el directorio [RDF](https://github.com/wguadalupeq/practicaSparQL/tree/main/RDF) de este repositorio en el servicio de consultas:
    - Si usamos el contenido del archivo `onlineQuerySELECT.rq` copiaremos la información y la usaremos en el servicio de consultas de la Wikidata nos devuelve la tabla que hemos construido mediante las consultas que hemos hecho.
    - Si usamos el contenido del archivo `onlineQueryCONSTRUCT.rq` copiaremos la información y la usaremos en el servicio de consultas de la Wikidata nos devuelve como serían las tripletas en una nueva estructura RDF que vamos a manejar.
3. Descargamos el archivo TSV detallado que se genera al usar el archivo `onlineQueryCONSTRUCT.rq` y lo modificamos para que tenga el formato Turtle a usar en el presente proyecto.
4. El archivo RDF en formato turtle una vez generado y se encuentra en el siguiente en el directorio [RDF](https://github.com/wguadalupeq/practicaSparQL/tree/main/RDF) con el siguiente nombre `RDF.ttl`.

Hasta ahora los pasos que hemos hecho es para extraer una estructura RDF nueva de Wikidata realizado consultas SparQL para obtener datos de investigaciones y trabajos científicos, digamos obras, que se basen sobre el tema de Ciencias de la Computación. De estos datos hemos extraído las siguiente características:

- Titulo
- Descripción
- Autor
- Tema
- Idioma
- Revista
- Fecha de Publicación
- URL



