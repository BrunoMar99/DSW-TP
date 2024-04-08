# Propuesta TP DSW

## Grupo
### Integrantes
* 47048 - Zarate, Exequiel
* 47094 - Martinez, Bruno
* 43814 - Aieta, Federico
* 42775 - Reinoso, Alfredo

### Repositorios
* [frontend app](http://hyperlinkToGihubOrGitlab)
* [backend app](http://hyperlinkToGihubOrGitlab)

## Tema
### Descripción
La empresa de nuestro trabajo es un supermercado "FAST" que quiere desarrollar una página web para que los clientes puedan realizar pedidos de forma online.

### Modelo
![MODELO](https://github.com/BrunoMar99/DSW-TP/assets/166306860/517113d7-2b01-42b9-b8f7-72184b8229b2)

## Alcance Funcional 

### Alcance Mínimo


Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Producto<br>2. CRUD Cliente<br>3. CRUD Repartidor<br>4. CRUD Proveedor|
|CRUD dependiente|1. CRUD Pedido {depende de} CRUD Cliente y Producto<br>2. CRUD Entrega {depende de} CRUD Repartidor y CRUD Cliente<br>3. CRUD Compra {depende de} CRUD Proveedor y CRUD Producto|
|Listado<br>+<br>detalle| 1. Listado de productos filtrado por tipo de producto, nro de producto y precio<br> 2. Listado de pedidos filtrado por rango de fecha, por nro de pedido<br> 3. Listado de entregas filtrado por rango de fecha y por cliente|
|CUU/Epic|1. Realizar un pedido<br>2. Dar de alta Cliente|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Producto<br>2. CRUD Cliente<br>3. CRUD Repartidor<br>4. CRUD Proveedor<br>5. CRUD Repartidor<br>6. CRUD Cajero<br>7. CRUD Repositor<br>8. CRUD Compra<br>9. CRUD Stock|
|CUU/Epic|1. Modificar Pedido<br>2. Dar de baja productos<br>3. Modificar productos|


### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

|Req|Detalle|
|:-|:-|
|Listados |1. Estadía del día filtrado por fecha muestra, cliente, habitaciones y estado <br>2. Reservas filtradas por cliente muestra datos del cliente y de cada reserve fechas, estado cantidad de habitaciones y huespedes|
|CUU/Epic|1. Consumir servicios<br>2. Cancelación de reserva|
|Otros|1. Envío de recordatorio de reserva por email|
