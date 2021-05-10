# Practica sobre SparQL
Este repositorio abarca las consultas SparQL a estructuras RDF.

Integrantes: 

- William Guadalupe 
- Danilo Blas
- Victor Chavez Bruno
- Bryan Asmat 

Para el presente proyecto se ha usado la base de conocimiento de la Wikidata realizando consultas online [Wikidata Query Service](https://query.wikidata.org/) con lo cual seguiremos los siguientes pasos para obtener la data.

1. Accederemos al enlace mencionado anteriormente
2. Podemos usar las consultas con extensión `.rq` que estan almacenadas en el directorio `RDF` de este repositorio:
  - Si usamos el archivo onlineQuerySELECT.rq copiando las lineas que hay en ese archivo y colocandolas en el servicio de consultas de la Wikidata nos devuelve la tabla que hemos construido mediante las consultas que hemos hecho
  - Si usamos el archivo onlineQueryCONSTRUCT.rq copiando las lineas que hay en ese archivo y colocandolas en el servicio de consultas de la Wikidata nos devuelve como serían las tripletas en una nueva estructura RDF que vamos a manejar
3. Descargamos el archivo TSV detallado y lo modificamos para que tenga el formato RDF a usar en el presente proyecto

Hasta ahora los pasos que hemos hecho es para extraer una estructura RDF nueva 
