# Endpoints API

Descripcion: Este documento listara los endpoints que se probaran con Swagger. Incluiria rutas para consultar productos, crear pedidos, agregar productos al pedido, modificar cantidades, confirmar pedidos y generar boletas.

Endpoints esperados:

- `GET /api/productos`
- `GET /api/productos?categoria=waffles`
- `GET /api/categorias`
- `POST /api/pedidos`
- `GET /api/pedidos/{id}`
- `POST /api/pedidos/{id}/productos`
- `PUT /api/pedidos/{id}/productos/{detalleId}`
- `DELETE /api/pedidos/{id}/productos/{detalleId}`
- `POST /api/pedidos/{id}/confirmar`
- `GET /api/pedidos/{id}/boleta`
