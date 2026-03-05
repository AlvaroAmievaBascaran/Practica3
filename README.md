# PRÁCTICA 3 - Persistencia y capa de servicio
### Endpoints
Método + Ruta - Descripción - Salida
-------------------------------------------------------------------------------------------------------------------------------------------
POST /api/carrito - Crear un carrito nuevo para un usuario - 201 Created + JSON del carrito creado
GET /api/carrito - Leer lista de carritos existentes - 200 OK + JSON con lista de carritos 
GET /api/carrito/{id_carrito} - Devuelve un carrito concreto con sus líneas - 200 OK + JSON del carrito
DELETE /api/carrito/{id_carrito} - Borra un carrito completo - 204 No Content  
POST /api/carrito/{id_carrito}/linea - añade una línea al carrito (suma unidades si existe artículo - 200 OK + JSON del carrito actualizado
-------------------------------------------------------------------------------------------------------------------------------------------
