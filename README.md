# Factory Method - Caso práctico

### Intención

Define una interface para crear un objeto, pero difiere a las subclases decidir cual clase instanciar. Factory Method diseña una clase difiriendo las instanciaciones a las subclases.

### Clasificación

Patrón Creacional

### Vista Estructural

![image](https://user-images.githubusercontent.com/55771796/174454444-cfcb5c8a-30f9-4503-af98-6f7254a28507.png)

### Vista Dinámica

![image](https://user-images.githubusercontent.com/55771796/174454462-58a4dd40-8000-4bb5-9108-48ec55b99260.png)

### Ejemplo Real

Mediante la implementación del patrón de diseño Factory Method crearemos una aplicación que sea capaz de conectarse a más de una base de datos, intercambiando de una a la otra, con tan solo realizar una simple configuración y sin una sola línea de código adicional.

Solución sin patrón Factory Method

![image](https://user-images.githubusercontent.com/55771796/174454541-919c5a22-48a1-4f9f-9d98-c9d2f6cf2d7b.png)

Solución con patrón Factory Method

![image](https://user-images.githubusercontent.com/55771796/174454568-6331ce8c-868f-4ce1-abcb-09a7e7a696f6.png)

![image](https://user-images.githubusercontent.com/55771796/174454584-e771ee62-05e5-426b-9353-3e554a544b71.png)


### Ejecucion

```
gradle run
```
