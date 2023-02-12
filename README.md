# Segunda-Pre-Entrega-Backend


## Consignas 

### Objetivos generales

Contarás con Mongo como sistema de persistencia principal
Tendrás definidos todos los endpoints para poder trabajar con productos y carritos.

### Objetivos específicos

Profesionalizar las consultas de productos con filtros, paginación y ordenamientos
Profesionalizar la gestión de carrito para implementar los últimos conceptos vistos.

### Formato

Link al repositorio de Github, sin la carpeta de node_modules

### Sugerencias

Permitir comentarios en el archivo
La lógica del negocio que ya tienes hecha no debería cambiar, sólo su persistencia. 
Los nuevos endpoints deben seguir la misma estructura y lógica que hemos seguido. 

### Se debe entregar

Con base en nuestra implementación actual de productos, modificar el método GET / para que cumpla con los siguientes puntos:
Deberá poder recibir por query params un limit (opcional), una page (opcional), un sort (opcional) y un query (opcional)

- [X] limit permitirá devolver sólo el número de elementos solicitados al momento de la petición, en caso de no recibir limit, éste será de 10
- [X] page permitirá devolver la página que queremos buscar, en caso de no recibir page, ésta será de 1
- [X] query, el tipo de elemento que quiero buscar (es decir, qué filtro aplicar), en caso de no recibir query, realizar la búsqueda general
- [X] sort: asc/desc, para realizar ordenamiento ascendente o descendente por precio, en caso de no recibir sort, no realizar ningún ordenamiento

