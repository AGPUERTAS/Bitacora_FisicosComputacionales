## **Actividad 3**
**¿Qué esperas ver en memoria (hipótesis)?**

- El vector esta almacenando punteros en este caso ```Particle*``` lo que hace que el vector gestione direcciones de memoria que apuntan hacía los datos. A su vez cada que se cree una prticula el objeto se agrega al heap y el vector tendra unicamente las direcciones de memoria de esos objetos.

![alt text](../../ejrecicios-capturas/Unidad3/Sesion2Actividad3.png)
 
 
**¿Qué puedes observar?**

- Se puede observar como el vector ``` particles``` cambia de tamaño (```size```) a medidda que se llama ```createRisingParticle()```. Tambien se peude obseravar que cada elemento del vector es un codigo hexadecimal (un puntero) y al desaparecer las particulas se peude ver como sus direccioones desaparecen de la  coleccion.

**¿Qué información te proporciona el depurador?**

- El depurador proporciona informacion como: Direcciones de memoria, Tamño y capacidad del vector y el estado de los atributos.
