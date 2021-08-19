# Comandos Básicos de MongoDB

* ` show dbs` : Nos muestra todas la bases de datos que estan creadas en el servidor
* ` db` : Nos muestra en la bd que nos encontremos actualmente
* ` help `: Nos obtiene los comando de ayuda que se usa
* ` db.help() `: Nos lista todos los comando que se utilizan en MongoDB
* `use nombreBD` : Crear base de datos y cambia a la que se creó (No lo crea hasta que se ingresen datos a esa BD).
* `db.NombreCollection.insert({})` : se insertan datos a NombreCollection puede ser cualquier nombre y dentro del campo van los documentos
* `db.dropDatabase()` : Elimina la BD actual.
* `show collections` : Nos lista todas las colecciones creadas dentro de BD
* `db.createCollection("NombreColeccion")` : Se Crea una coleccion de datos
* `db.NombreCollection.drop()` : Elimina la Coleccion que se escriba.
* `db.NombreCollection.find()` : Muestra todos los datos que estan registrados en la coleccion NombreCollection
* `db.NombreCollection.find().pretty()` : Muestra todos los datos que estan registrados en la coleccion NombreCollection de forma ordenada y con un ID

![](https://github.com/elmergustavo/MongoDB-Java/blob/master/img.jpg)



