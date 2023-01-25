# ![android-icon-48x48](https://user-images.githubusercontent.com/6616670/203347014-4b5f6081-4bff-4ffc-bbd0-e18f4f5559bc.png) CPANAX: Desarrollador en React

La presente es evaluar sus habilidades tecnicas en base a una serie de desafíos que les planteare mas adelante, ustedes deciden cual tomar y hasta donde llegar.

Sientanse libres de usar estos desafíos en sus cuentas de git para sus portafolios.

*Nota: Deben realizar los primeros 3 desafios, el ultimo es un extra pero opcional.*

Se evaluara: 
 - Diseño de las tarjetas.
 - Diseño del panel (si aplica en el requerimiento).
 - Diseño de la Pagina.
 - Habilidad en seguir instrucciones.
 - Habilidad en la ejecución de la tarea.
 - Conocimientos en React
 - Manejo de Formularios (si aplica en el requerimiento).
 - Majejo de Estados.
 - Optimizaciones de codigo.
 - Optimizaciones de render.
 - Estimación de tiempo vs cumplimiento por desafío.
 - Despliege en algún host como [netlify](https://www.netlify.com/), [vercel](https://vercel.com/) o el que estes usando actualmente.


## Desafío 1: Elaborar una lista de productos

Se requiere obtener de un servicio los productos y elaborar una lista, para ello sera necesario:

 - Poder cambiar la cantidad de tarjetas por filas a mostrar, por defecto mostrar 4 tarjetas en la fila.
 - Paginación 
 - Representar: Imagen, titulo y marca
 - Modal que aparecera al momento de darle click a la tarjetay debe apaecer una galeria de imagenes.


**Libreria para realizar la petición**: [axios](https://www.npmjs.com/package/axios)

**URL del servicio**: https://dummyjson.com/products 



## Desafío 2: Elaborar una Tabla con los usuarios de la app

Se requiere obtener de una servicio la información de los usuarios de la aplicación, para ello sera necesario:

 - Paginación de los datos
 - Los campos a representar: firstName, lastName, age, username, ip, image (opcional)
 - Modal que muestre información complementaria del usuario.

**Libreria para Tablas**: [react-base-table](https://www.npmjs.com/package/react-base-table)

**Libreria para realizar la peticion**: [axios](https://www.npmjs.com/package/axios)

**URL del servicio**: https://dummyjson.com/users



## Desafío 3: Elaborar un Diagrama de Recursos

Se requiere elaborar un diagrama donde se represente el flujo de la aplicacion, para ello sera necesario disponer:

 - Panel lateral donde se tenga las opciones que permitan arrastrar y soltar.
 - Al dar click en el header de la tarjeta llamar una modal con un Formulario que permita cambiar el titulo y descripciones de la tarjeta.
 - Un boton + (Agregar) en la tarjeta para crear un nuevo nodo generico.

**Libreria sugerida para el diagrama**: [reactflow](https://www.npmjs.com/package/reactflow)

**Libreria sugerida para los formularios**: Queda a su eleccion

**Libreria sugerida para la modal**: Queda a su eleccion

**Archivo de datos**: [data.js](https://github.com/ajimenezg/cpanax-desafio/blob/main/diagrama/data.js)


## Desafío 4 (Opcional): Elaborar un Kanban (Trello)

Se requiere elaborar kanban donde contenga un panel de tareas que se arrastran a las columnas, para ello sera necesario disponer:

 - Panel lateral donde se tenga las tareas que permitan arrastrar y soltar.
 - Poder mover la tarjeta a diferentes Columns/Groups.
 - Un boton + (Agregar) en el final de la columna para agregar una nueva tarea.

**Libreria sugerida para el diagrama**: [@dnd-kit](https://www.npmjs.com/package/@dnd-kit/core)

**Libreria sugerida para la modal**: Queda a su eleccion

