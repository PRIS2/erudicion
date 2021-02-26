# Erudición

Repositorio de los miembros del grupo Erudición compuesto por:

* Aarón Blanco Álvarez
* Alejo Martín Arias Filippo
* Francisco Hernández Montoya
* Juan Pablo Grosso Tarazaga
* Miguel Ángel Puertas Sánchez
* Ramón Francisco Ramos Tristán

Proyecto basado en Latex.

# Reuniones

- La reunión inicial del grupo se realizó el sábado 13 de febrero de 2020 a las 15:15 horas con la asistencia de todos los miembros hicimos un primer modelo mediante la utilización de figuras. La profesora propuso una modificación del modelo para una mayor completitud de la tarea.  

![Primera iteración](/imagesReadme/pruebaCapturas.png "Primera iteración")
- La segunda reunión se realizó el jueves 18 de febrero de 2020 a las 9:15 horas excusando su ausencia Miguel Ángel Puertas Sánchez y Ramón Francisco Ramos Tristán, realizamos la modificación propuesta por la profesora y efectuamos una segunda propuesta quedando únicamente la creación de la sección del índice.
![Primera rueba con newfloats](/imagesReadme/newfloat.png "Primera rueba con newfloats")
![Creacion de capturas en su propio entorno](/imagesReadme/figuras_capturas.png "Creacion de capturas en su propio entorno")
- La cuarta reunión se realizó el sábado 20 de febrero de 2020 a las 10:00 horas terminó de realizar el índice únicamente Juan Pablo Grosso Tarazaga.
- La última reunión se realizó el viernes 26 de febrero de 2020 a las 15:00 horas con la asistencia de todos los miembros. Se llevó a cabo la documentación del proyecto.
- Aquí mostramos el panel con todos los distintos issues y la información asociada a ellos que tenemos en github.
![Lista de capturas](/imagesReadme/organizacion_de_issues.png "Panel del proyecto")

# Documentación

Se realizarón bastantes procesos de documentación para la tarea encomendada, sus respectivos enlaces se encuentran en el proyecto del equipo:

- Instalalación de Latex y configuración de VSCode.
- Manipulación y creación de objetos flotantes.
- Adición de autores a Latex.

# Tareas realizadas

- Crear versión preliminar del objeto "Captura" con \newfloat
- Incorporar una opción en el documento simulando a la opción "print" que en caso de que se declare, esta pueda incorporar en el documento un nuevo tipo de elemento flotante latex.
- Los flotantes deben contener una imagen que sea una captura de pantalla independiente del resto de figuras.
- Generar listado independiente que incluya solo capturas.
- Añadir tareas al main.tex.
- Creación de índices.

# Proceso de desarrollo

Tras realizar los cambios propuestos tras la primera iteración, el resultado del codigo quedaria del siguiente modo.

- La primera parte sería la importacion del paquete **newfloat** y la creacion de un nuevo entorno en **UAL.sty**.

![Creacion del entorno](/imagesReadme/nuevo_entorno.png "Creacion del entorno")

- Creamos un comando con el cual indicamos los parametros que se la pesaran ademas de centrar la imagen.

![Metodo print](/imagesReadme/funcion_print.png "Metodo print")

- Aquí podremos ver un ejemplo de implementación del método con sus respectivos parametros 
en el archivo **contenido2.tex** y como queda el resultado.

![Metodo print](/imagesReadme/ejemplo_de_funcionamiento.png "Metodo print")
![Capturas](/imagesReadme/capturas.png "Capturas")

- Por último se ha añadido la lista de capturas justo debajo del índice de listados en el archivo **indicesyrefe.tex**.
-
![Lista de capturas](/imagesReadme/listado_de_capturas.png "Lista de capturas")


