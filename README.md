Proyecto ejecutable en Spring Tool.
- Java 21
- Spring Boot 3
- Spring Security + JWT
- BCrypt
- Spring Data JPA
- MySQL
- Maven

## Credenciales iniciales para iniciar sesión como admin en la página web

- Email: admin@ventaslibros.com
- Password: Admin12345

## Base de datos subida en la web local 
## Endpoints principales

https://libroclouds.onrender.com/

### Libros
- GET /api/libros
- GET /api/libros/{id}
- GET /api/libros/categoria/{categoriaId}
- POST /api/libros
- PUT /api/libros/{id}
- DELETE /api/libros/{id}

### Categorías
- GET /api/categorias

### Clientes
- GET /api/clientes
- POST /api/clientes

### Ventas
- GET /api/ventas
- GET /api/ventas/{id}
- POST /api/ventas
- PATCH /api/ventas/{id}/anular

## Reglas de negocio
- No se elimina físicamente un libro; se marca como eliminado e INACTIVO.
- El ISBN no puede repetirse.
- El libro debe pertenecer a una categoría activa.
- El stock no puede ser negativo.
- Una venta descuenta stock.
- Una venta anulada devuelve stock.

## Página web en la nube (primero debes visitar https://libroclouds.onrender.com/ y esperar a que cargue)
https://portfolio-10926.web.app/
