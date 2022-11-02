# Petstore (net-mvc-kata)
Ejercicio de entrenamiento para la implementación de aplicaciones .Net MVC

## Contexto
Petstore, un negocio local lleva un registro de todas las mascotas de sus sucursales. Para administrar el catálogo expone una serie de servicios en la siguiente dirección: [Swagger Petstore](https://petstore.swagger.io/).

## Ejercicio
Para facilitar la visualización de reportes es necesario implementar una interfaz gráfica que presente una tabla como la que se muestra a continuación:

| ID                  | NOMBRE MASCOTA | ESTADO    |
|---------------------|----------------|-----------|
| 9223372036854308333 | doggie         | available |
| 9223372036854308337 | doggie         | available |
| 9223372036854308339 | doggie         | available |

Para ello, se debe obtener la información del método [findPetsByStatus](https://petstore.swagger.io/#/pet/findPetsByStatus), es decir,se debe consumir dicho servicio.

## Recomendaciones
- Tu implementación debe considerar que el servicio te entregará varios registros.
- La solución debe ser simple, pero recordando que es importante mantener buenas prácticas durante la implementación.
- Para la resolución de este caso es necesario trabajar con .Net Core 2.1 en adelante o .Net 5 en adelante (MVC).
- Cualquier plus que consideres importante para esta implementación es bienvenido.
- Una vez finalizada tu implementación debe subirla a Github y compartir el enlace.
