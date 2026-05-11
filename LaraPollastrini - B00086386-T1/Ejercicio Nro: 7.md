# Ejercicio Nro: 7
## Enunciado
Dar un ejemplo de cada uno de los cuellos de botellas analizados anteriormente en el paper de Brooks
## Resolución
Cuellos de botella del Paper de Brooks:

Ejemplo: Aplicación para una pizzeria
* Complejidad: No es solo "pedir pizza". Hay que conectar el inventario, el horario del repartidor, los cupones de descuento y la ubicación del cliente. Si cambias algo en los cupones, se podría romper sin querer el sistema de pagos. Como hay tantas piezas conectadas de forma única, el sistema muchas veces es difícil de entender.
* Conformidad: La aplicación de pizzas debe aceptar pagos con una tarjeta específica porque el banco lo exige así, o debe calcular el impuesto exactamente como dice la ley de tu ciudad. El software que hacemos tiene que "acomodarse" a reglas externas que son obligatorias.
* Cambiabilidad: La aplicación en la parte de pagos ya funcionaba bien, pero de repente los bancos o billeteras virtuales cambian su forma de trabajar entonces, ahora toca modificar y acoplar el sistema a la nueva forma de pago que exigen para que los clientes puedan seguir pagando. El software siempre recibe presión para cambiar por cosas externas.
* Invisibilidad: Si entras a la pizzería, podemos ver el horno y las mesas, y entender cómo funciona el local. Pero en la app, no se puede "ver" el camino que sigue el pedido. No existe un dibujo único que te muestre todo el funcionamiento a la vez; son solo procesos invisibles en la memoria que en muchos casos cuesta mucho imaginar y explicar.
