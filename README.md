# Ejercicio01
Ejercicio 01

## Etapa 01. Descripción del problema
Se requiere un programa en Java para convertir una cantidad de dinero en otros tipos de monedas (al menos a cinco tipos de monedas distintas). 

## Etapa 02. Definición de la solución

~~~
- Entrada
  float cantidad
  String moneda1, moneda2, moneda3, moneda4, moneda5
  double conversion
  
- Proceso
  Solicitar moneda a convertir
  Solicitar cantidad a convertir
  Solicitar moneda para procesar conversión
  
  Si el monto es mayor o igual que cero entonces se convertirá a la moneda deseada
  Si el monto es menor que cero entonces se cancela la operación
 
- Salida
  
  +----------+---------------+---------------------+----------------+
  | CANTIDAD | MONEDA ORIGEN | CANTIDAD CONVERTIDA | MONEDA DESTINO |
  +----------+---------------+---------------------+----------------+
  |       10 |          DLLS |              189.79 |            MXN |
  +----------+---------------+---------------------+----------------+
  |       10 |          DLLS |             0.00043 |            BTC |
  +----------+---------------+---------------------+----------------+
 ~~~
 
 
 ## Etapa 03. Diseño la solución
 
 ![](https://github.com/edgardegantea/Ejercicio01/blob/master/Diagrama%20de%20clases.png)
