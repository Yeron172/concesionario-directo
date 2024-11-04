# concesionario-directo
El universo es un concesionario de automóviles, de los clientes se conocen los datos habituales. También de los coches de los vendedores y las ventas.

 Un coche puede ser recomprado a un cliente.

universo.discurso.fin
#---------------------------------------------------------------------------------------
v2
universo.discurso.comienzo

	concesionario de automóviles.
-cliente: se conocen los datos habituales,
-coche: se conocen los datos habituales,
-vendedor: se conocen los datos habituales,
-venta: se conocen los datos habituales,

Un coche puede ser recomprado a un cliente.

universo.discurso.fin

#---------------------------------------------------------------------------------------
v3
universo.discurso.comienzo
-concesionario(de automóviles)
-cliente(,,)
 -coche(,,)
-vendedor(,,)
 -venta(,,)
-recompra(de coche)(por cliente)

universo.discurso.fin

#---------------------------------------------------------------------------------------
v4 (con diseño)

-concesionario(de automóviles)
-cliente(dni, nombre, ape, teléfono, dirección,...)
 -coche(numBastidor,matrícula, marca, modelo , color)
-vendedor(,,)
 -venta(,,)
-recompra(de coche)(por cliente)





