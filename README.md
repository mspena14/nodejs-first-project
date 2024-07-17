# nodejs-first-project

1. **¿Qué es el filesystem (fs) en Node.js y para qué se utiliza?**
    **R//** Es un módulo de node que nos permite interactuar con el sistema de archivos de la computadora. Se puede leer y dar contenido a un archivo o escribir en él e incluso abrilos, también permite crear y eliminar directorios, en resumen permite administrar los archivos en la computadora.

2. **¿Qué es un middleware en Express y cuál es su propósito?**
**R//** Es una función que se puede ejecutar en medio del ciclo de solicitud-respuesta, o sea, que puede ejecutar funciones en medio de una petición o una tarea que se ejecuta. Puede analizar los datos de una solicitud, agregar respuestas e incluso puede finalizar con el ciclo de solicitud-respuesta.

3. **¿Qué es un endpoint en una API RESTful y cuál es su función?**
**R//** Es una ubicación donde se encuentra la información a la que queremos acceder a través de la API. Su función es brindar un punto de llegada a la API y proporcionar la respuesta que busca esta API si la hay.

4. **¿Qué son los verbos HTTP y cuáles son los más comunes?**
**R//** Los verbos HTTP son los que nos permiten interactuar con los endpoints mediante la API y los que le dan la instrucción de qué hacer a esta API, los más comunes son: GET, POST, PUT, PATCH y DELETE.

5. **¿Qué es JSON y por qué es utilizado en las API RESTful?**
**R//** JSON es el formato que se utiliza para el intercambio de datos en entre el servidor y el cliente. Este es utilizado en las API RESTful ya que este formato de escritura permite dicha conexión entre dos partes, siendo sencillo de leer y fácil de implementar.

En lo que respecta al envio de datos a lo largo de los verbos http responde:

    ¿Qué es el body de una petición?
    R// El body de una petición son los datos que se envían al servidor que contienen la solicitud que se está realizando.

    ¿Qué es el body de una respuesta?
    R// El body de una petición son los datos que traen la respuesta a lo que se envió en el body de petición.

    ¿Qué es el query de una petición?
    R// Una query es una consulta que se realiza por medio de la url para determinar los parametros que buscará la API, normalmente se establece como clave/valor.

    ¿Qué es el params de una petición?
    R// Son los que indican las rutas especificas que se tomarán en la consulta, más comúmente utilizado con el id.

6. **En lo que respecta al verbo POST responde:**

    ¿Qué es un verbo POST y cuál es su propósito?
    R// El verbo POST se encarga de agregar un nuevo elemento a la ruta proporcionada.

    ¿Cuándo se utiliza un verbo POST?
    R// Cuando queremos crear desde 0 un elemento y guardarlo en nuestro JSON o formato de almacenamiento.

    ¿En qué se diferencia un verbo POST de los otros verbos HTTP como GET, PUT y DELETE?
    R// POST se diferencia a todos ellos ya que es el único que se encarga de agregar información los demás se encargan de obtener datos, modificar datos y eliminar datos respectivamente.

    ¿Como se envian datos en un verbo POST?
    R// Los datos se envían a través del POST por medio del body, normalmente se crea un objeto que contiene la solicitud y los datos de esta.

7. **En lo que respecta al verbo GET responde:**

    ¿Qué es un verbo GET y cuál es su propósito?
    R// El verbo GET es el encargado de solicitar datos al servidor y su proposito es brindarlos al cliente.

    ¿Cuándo se utiliza un verbo GET?
    R// Este se utiliza cuando queremos obtener datos que se encuentran alojados en el servidor, ya sean datos generales o especificos.

    ¿En qué se diferencia un verbo GET de los otros verbos HTTP como POST, PUT y DELETE?
    R// Se diferencia de los demás en que este es utilizado especificamente para devolver datos que se encuentran en el servidor al cliente, mientras que los demás no tienen esta funcionalidad.

8. **En lo que respecta al verbo PUT responde:**

    ¿Qué es un verbo PUT y cuál es su propósito?
    R// El verbo PUT es que permite modificar los datos que ya se encuentran en el servidor y tiene como proposito el poder interactuar con estos datos modificandolos lo que lo hace dinamico a la hora de manejar los datos.

    ¿Cuándo se utiliza un verbo PUT?
    R// El verbo PUT se utiliza cuando queremos que la API actualice los datos de un elemento en el servidor.

    ¿En qué se diferencia un verbo PUT de los otros verbos HTTP como POST, GET y DELETE?
    R// Este verbo a diferencia de los mencionados nos permite alterar los datos que están en el servidor, no trae los datos sino que los actualiza y tampoco los elimina.

9. **En lo que respecta al verbo DELETE responde:**

    ¿Qué es un verbo DELETE y cuál es su propósito?
    R// El verbo DELETE el que indica que se elimine algún elemento del servidor, su proposito es poder desechar lo que no sea necesario en nuestro servidor.

    ¿Cuándo se utiliza un verbo DELETE?
    R// Se utiliza cuando no queremos conservar más algún dato del servidor y lo queremos desechar.

    ¿En qué se diferencia un verbo DELETE de los otros verbos HTTP como POST, GET y PUT?
    R// El verbo DELETE es el único que nos permite desechar datos que se encuentran en el servidor.

10. **¿Qué es un status code y cuáles son los más comunes?**
R// Los status code son las respuestas que nos da HTTP a la hora de realizar alguna consulta. 
Los más comunes son:
- 200
- 201
- 204
- 304
- 400
- 401
- 403
- 404
- 409
- 410
- 500

11. **¿Cuales son los status code mas comunes para el verbo POST?**
**R//** Para el verbo POST:

    200 OK: Indica que la solicitud ha tenido éxito.
    201 Created: Se utiliza cuando se ha creado un nuevo recurso como resultado de la solicitud.
    400 Bad Request: Indica que la solicitud no pudo ser procesada debido a errores del cliente.
    401 Unauthorized: Indica que se necesita autenticación para acceder al recurso.
    404 Not Found: Indica que el recurso solicitado no fue encontrado.

12. **¿Cuales son los status code mas comunes para el verbo GET?**
**R//** Para el verbo GET:

    200 OK: Indica que la solicitud ha tenido éxito y se devolverá el contenido solicitado.
    400 Bad Request: Indica que la solicitud no pudo ser procesada debido a errores del cliente.
    401 Unauthorized: Indica que se necesita autenticación para acceder al recurso.
    403 Forbidden: El servidor entiende la solicitud, pero se niega a autorizarla.
    404 Not Found: Indica que el recurso solicitado no fue encontrado.

13. **¿Cuales son los status code mas comunes para el verbo PUT?**
**R//** Para el verbo PUT:

    200 OK: Indica que la solicitud ha tenido éxito.
    400 Bad Request: Indica que la solicitud no pudo ser procesada debido a errores del cliente.
    401 Unauthorized: Indica que se necesita autenticación para acceder al recurso.
    403 Forbidden: El servidor entiende la solicitud, pero se niega a autorizarla.
    404 Not Found: Indica que el recurso solicitado no fue encontrado.

14. **¿Cuales son los status code mas comunes para el verbo DELETE?**
**R//** Para el verbo DELETE:

    200 OK: Indica que la solicitud de eliminación ha sido exitosa.
    204 No Content: Indica que la solicitud de eliminación ha sido exitosa y que no hay contenido para devolver.
    400 Bad Request: Indica que la solicitud no pudo ser procesada debido a errores del cliente.
    401 Unauthorized: Indica que se necesita autenticación para acceder al recurso.
    403 Forbidden: El servidor entiende la solicitud, pero se niega a autorizarla.
    