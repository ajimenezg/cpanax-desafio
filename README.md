# CPANAX: Desarrollador en React

La presente es evaluar sus habilidades tecnicas en base a una serie de desafios que les planteare mas adelante, ustedes deciden cual tomar y hasta donde llegar.


Se evaluara: 
 - Diseño de las tarjetas.
 - Diseño del panel (si aplica en el requerimiento).
 - Diseño de la Pagina.
 - Habilidad en seguir instrucciones.
 - Habilidad en la ejecucion de la tarea.
 - Conocimientos en React
 - Manejo de Formularios (si aplica en el requerimiento).
 - Majejo de Estados
 - Optimizaciones de codigo
 - Optimizaciones de render
 - Estimacion de tiempo vs cumplimiento por desafio.


## Desafio 1: Elaborar una lista de productos

Se requiere obtener de un servicio los productos y elaborar una lista, para ello sera necesario:

 - Poder cambiar la cantidad de tarjetas por filas a mostrar, por defecto mostrar 4 tarjetas en la fila.
 - Paginacion (No obligatorio)
 - Representar: Imagen, titulo y marca
 - Opcional: Modal al darle click a la tarjeta con galeria de imagenes.


**Libreria para realizar la peticion**: [axios](https://www.npmjs.com/package/axios)

**URL del servicio**: https://dummyjson.com/products 



## Desafio 2: Elaborar una Tabla con los usuarios de la app

Se requiere obtener de una servicio la informacion de los usuarios de la aplicacion, para ello sera necesario:

 - Paginacion de los datos
 - Los campos a representar: firstName, lastName, age, username, ip, image (opcional)
 - Opcional: Modal que muestre informacion complementaria del usuario.

**Libreria para Tablas**: [react-base-table](https://www.npmjs.com/package/react-base-table)

**Libreria para realizar la peticion**: [axios](https://www.npmjs.com/package/axios)

**URL del servicio**: https://dummyjson.com/users



## Desafio 3: Elaborar un Diagrama de Recursos

Se requiere elaborar un diagrama donde se represente el flujo de la aplicacion, para ello sera necesario disponer:

 - Panel lateral donde se tenga las opciones que permitan arrastrar y soltar.
 - Al dar click en el header de la tarjeta llamar una modal con un Formulario que permita cambiar el titulo y descripciones de la tarjeta.
 - Un boton + (Agregar) en la tarjeta para crear un nuevo nodo generico.

**Libreria sugerida para el diagrama**: [reactflow](https://www.npmjs.com/package/reactflow)

**Libreria sugerida para los formularios**: Queda a su eleccion

**Libreria sugerida para la modal**: Queda a su eleccion

**Archivo de datos**: [data.js](https://github.com/ajimenezg/cpanax-desafio/blob/main/diagrama/data.js)

