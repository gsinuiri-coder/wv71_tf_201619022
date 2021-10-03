## Algoritmo 1

Autor: Giancarlo Sinuiri

Técnica principal: dijkstra

Para resolver el problema VRP, propongo el algoritmo dijkstra por los siguientes motivos:

- Buscar el camino óptimo de todos los puntos de entrega contra todos.
- Limitar los puntos de entrega en un área.
- Recorrer cada posibilidad e ir calculando el costo.
- Si la distancia de otro punto es más largo a la distancia del almacen, retornar al almacen y eso seria un vehiculo de carga.
- Verificar si ya se entregaron toda la carga del vehiculo.
- Verificar el kilometraje en recorrido.
- Verificar en el punto de entrega actual, si la capacidad de recorrido es suficiente para llegar al almacen.
