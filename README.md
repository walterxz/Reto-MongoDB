# Reto-MongoDB

## Base de datos noSQL

- Debes realizar base de datos de los resultados de las olimpiadas de matemáticas de estudiantes en edades de 16 - 20 años. Cada examen está compuesto por 3 módulos (estadística, conjuntos y ecuaciones), los cuales cuentan con calificación independiente y el resultado final por cada estudiante es el promedio de los 3 módulos.

-Se creo un cluster en Atlas MongoDB

![Mongo1](./screenshots/CaptureA.JPG)

- Se creo una Base de datos olympics
- Se le asigno un usuario
- Se permitio acceso a la ip local
- Se creo la conexion con Mongo Atlas a través de la URL

![Mongo1](./screenshots/CaptureB.JPG)

- Se crearon los esquemas de los Modulos y Calificaciones 

![Mongo1](./screenshots/CaptureC.JPG)

- Se creo los documentos de los estudiantes

![Mongo2](./screenshots/Capture5.JPG)

- Se crearon los documentos para los Modulos de las calificaciones

![Mongo2](./screenshots/CaptureD.JPG)

- Se creo la relación de usuarios, donde se tiene un arreglo de objetos, donde un atributo es la fecha de aplicación y el siguiente el Id de las calificaciones por Modulo que se obtuvieron.

![Mongo2](./screenshots/CaptureE.JPG)
