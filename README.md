# VRPSPD - Vehicle Routing Problem with Simultaneous Pickup and Delivery

Este repositorio está enfocado en el estudio del problema **VRPSPD** (*Vehicle Routing Problem with Simultaneous Pickup and Delivery*), una variante del problema de ruteo de vehículos donde una flota debe realizar entregas y recogidas de productos de manera simultánea.

El objetivo principal del proyecto es analizar cómo optimizar rutas de vehículos considerando restricciones de capacidad, demandas de entrega, cantidades de recogida y minimización de la distancia o costo total recorrido.

## Descripción del problema

El **VRPSPD** consiste en determinar un conjunto de rutas para una flota de vehículos que salen desde un depósito, visitan a distintos clientes y luego regresan al punto de origen.

A diferencia de otros problemas de ruteo, en este caso cada cliente puede requerir una entrega y, al mismo tiempo, generar una recogida. Esto significa que la carga del vehículo cambia durante todo el recorrido, ya que disminuye al entregar productos y aumenta al recoger otros.

Por esta razón, el problema debe asegurar que la capacidad máxima del vehículo no sea superada en ningún momento de la ruta.

## Objetivo del proyecto

El propósito de este proyecto es comprender, modelar y analizar el problema VRPSPD mediante el uso de herramientas de optimización de rutas.

Los objetivos principales son:

- Estudiar el funcionamiento del problema VRPSPD.
- Identificar sus principales restricciones.
- Analizar el comportamiento de las rutas generadas.
- Utilizar LKH-3 como referencia para la resolución del problema.
- Evaluar soluciones considerando distancia total, capacidad y factibilidad de las rutas.

## Herramienta de referencia

Para este proyecto se utiliza como referencia **LKH-3**, una extensión del solver Lin-Kernighan-Helsgaun.

Esta herramienta permite resolver problemas del viajante y problemas de ruteo de vehículos con restricciones. Dentro de sus variantes soportadas se encuentra el problema **VRPSPD**, por lo que resulta adecuada como base para estudiar este tipo de problemas de optimización.

## Conceptos principales

- **VRP:** Problema de ruteo de vehículos.
- **VRPSPD:** Problema de ruteo de vehículos con entregas y recogidas simultáneas.
- **Depósito:** Punto inicial y final desde donde salen los vehículos.
- **Cliente:** Nodo que debe ser visitado dentro de una ruta.
- **Entrega:** Cantidad de producto que el vehículo deja en un cliente.
- **Recogida:** Cantidad de producto que el vehículo retira desde un cliente.
- **Capacidad:** Límite máximo de carga que puede transportar un vehículo.
- **Ruta:** Secuencia de clientes visitados por un vehículo.

## Funcionamiento general

El proceso general del proyecto consiste en seleccionar una instancia del problema VRPSPD, definir los parámetros necesarios para su resolución, ejecutar el solver LKH-3 y analizar las rutas obtenidas.

Luego, se revisa si la solución cumple con las restricciones del problema, especialmente la capacidad de los vehículos y la correcta atención de las entregas y recogidas de cada cliente.

Finalmente, se evalúa la calidad de la solución considerando la distancia total recorrida y la factibilidad de las rutas generadas.

## Importancia del problema

El VRPSPD es importante en contextos logísticos donde una empresa no solo debe entregar productos, sino también retirar materiales, devoluciones, residuos o insumos desde los mismos clientes.

Este tipo de problema puede aplicarse en distintas áreas, como distribución de productos, logística inversa, recolección de residuos, transporte de mercancías y servicios de reparto con devolución.

Resolver este problema de forma eficiente permite reducir costos operacionales, mejorar el uso de los vehículos y optimizar los tiempos de distribución.

## Resultado esperado

Se espera obtener rutas eficientes que permitan reducir la distancia total recorrida, cumplir con las demandas de entrega y recogida, y respetar la capacidad máxima de los vehículos.

Además, se busca comprender cómo el uso de herramientas como LKH-3 puede apoyar la resolución de problemas complejos de optimización logística.

## Integrantes

- Vicente Jiménez
- Cristóbal Osorio
- Nicolás Sandoval

## Referencia

Keld Helsgaun. **LKH-3: An Extension of the Lin-Kernighan-Helsgaun TSP Solver for Constrained Traveling Salesman and Vehicle Routing Problems**.

Sitio oficial de LKH-3:  
http://webhotel4.ruc.dk/~keld/research/LKH-3/
