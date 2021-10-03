## Integrantes:

- Giancarlo Sinuiri Mozombite u201619022

## Descripción de datos de vehículos de entrega, calcular costo

1. Combustible.
  - El costo se va a calcular segun la distancia del recorrido.
  - Tanque lleno de combustible tiene un recorrido máximo de 50km.
  - S/10 costo por 1km.

2. Capacidad de carga.
  - El costo es unico, S/100.
  - 1 tonelada capacidad de carga.

   Se prodria plantear como reto optimizar la capacidad de carga.

## Definir espacio de búsqueda, estado inicial, posible estado final, transiciones.

1. Estado inicial.

![inicial](https://user-images.githubusercontent.com/71910095/135761979-a8ce2089-fb20-47ef-a88e-bc791dbe1fa1.PNG)

2. Estado final

![final](https://user-images.githubusercontent.com/71910095/135761999-fca6ae1b-0f02-4405-a441-7342623799d4.png)

3. Transiciones.

- Distancia máxima a los lados 9km.
- Capacidad de recorrido 50km
- Movimiento hacia los puntos no recorridos.
- Si todos los puntos de entrega estan visitados, regresar al almacen por el camino más corto.

4. Espacio de Búsqueda.

![espacio de busqueda - copia](https://user-images.githubusercontent.com/71910095/135762117-6d4905fe-bced-4272-949d-9c76964dee12.png)

 ## Reporte de actividades.
 
 1. Giancarlo Sinuiri

- Actualizar lista de integrantes. (issue)
- Generar primera versión de almacenes.csv
- Generar primera versión de puntos_entrega.csv
- Generar descripción de datos de vehículos de entrega indicando según su criterio, calculo de costo.
- Definir espacio de búsqueda, estado inicial, posible estado final, transiciones.
- Definir algoritmo integrante 1 en alto nivel con posible análisis asintótico.
- Producir reporte de actividades.
- Incluir URL de video en youtube (u otro servicio) no listado (compartido por URL, privado) en el archivo README.md de un video elaborado de máximo 1 minuto explicando actividades realizadas.

