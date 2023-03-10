# Crear-Diagrama

### ENUNCIADO CONCIERTO:
  
Una empresa de organización de eventos necesita almacenar al público, al artista y a los segurata. 

De todos estos debemos saber el 
* Nombre
* Número 
* Email.

También debemos guardar del artista: 
* Género.
 Un artista puede ser capaz de cantar varias canciones, en cambio, una canción, solo puede ser cantada por un artista. Aparte las canciones que va a cantar(una lista). 

 Por otra parte almacenar a las personas que se van a encargar de la seguridad; 
*  ID_seguridad 
* Edad

Debemos poner que cada segurata tiene asignado a un segurata superior. Ya que un segurata superior se encarga de uno o más seguratas, en cambio un segurata superior sólo puede ser una persona.

Además cada segurata debe tener una app de control de acceso para poder controlar al público, por lo que un segurata sólo puede tener una app de control de acceso y la app de acceso la tienen varios seguratas.


Del público debemos saber:
* DNI
* Edad (mayores de 18 años)
* Nivel educativo 
* Ocio habitual.


El público únicamente puede comprar una entrada, es decir, es una entrada por persona. Por lo que una persona no puede tener más de una persona.

Entonces debemos almacenar las entradas:

* Identificador de entradas
* Nombre
* Precio 
* Fecha

También cada entrada tiene un formulario que se debe de completar. Sólo se puede hacer un formulario por entrada. 

Las entradas pueden ser online o compradas en Taquilla.

En las entradas online muestra:
* Número de entradas QR 

En las entradas de Taquilla mostrar:
* Número de venta 
* Hora en la que fué comprada.

Incluye getters y setters.  

# Solución:

![trabajoEntInventarBUENOOO drawio](https://user-images.githubusercontent.com/114684316/224291524-4a7f5bed-883a-4810-8cfa-aa093e065122.png)



###### Página de referencia:
[[Cómo organizar un concierto: 10 puntos clave (weezevent.com)](https://weezevent.com/es/blog/como-organizar-un-concierto-10-puntos-clave/)]


