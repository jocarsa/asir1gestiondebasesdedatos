Tengo un cliente que tiene una empresa, y ese cliente, tiene, por una parte, clientes, esa empresa, que es de papelería, tiene productos - cuando un cliente entra, realiza un pedido (y en cada pedido se pueden comprar un número de productos)

Entidad:
Clientes
-Id de cliente
-nombre
-dni/cif/identificacion
-telefono
-correo
-Direccion

Entidad:
Productos
-Id del producto
-Nombre del producto
-Base imponible
-Peso
-Dimensiones

Entidad:
Pedidos
-Id del pedido
-Id de cliente - Foreign Key a clientes
-Cantidad que se ha pedido
-Id Producto - Foreign Key a productos
-Total de precio (campo calculado)
(Problema de cardinalidad 1:n lineas de pedido)


