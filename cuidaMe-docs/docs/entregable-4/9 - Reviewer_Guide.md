# Reviewer Guide

**Autor(es):**
- Diáñez Suárez, Daniel
- León Madroñal, Juan Carlos
- García Galocha, Rafael David
- Castellano Alonso, Álvaro

|**Fecha**|**Versión**|
| :-: | :-: |
|12/02/2024|v1.0|


## Introducción
Este documento establece los pasos necesarios para preparar a los equipos para la revisión de software. Este documento es esencial para garantizar la calidad y fiabilidad de nuestros proyectos. Nos centraremos en dos aspectos fundamentales: la elaboración de una guía de revisión y la comprensión de las condiciones que podrían llevar al fallo del software. La guía proporcionará una estructura clara y detallada para que otros puedan entender y ejecutar adecuadamente los escenarios de uso en nuestra aplicación. Por otro lado, la comprensión de las condiciones de fallo nos ayudarán a anticiparnos a posibles problemas o fallos software y asegurar la calidad de nuestro producto. Estos elementos son fundamentales para garantizar la calidad y fiabilidad del software en cada etapa de su desarrollo y despliegue.


## Información necesaria
Aquí se listan credenciales (usuarios y contraseñas) de al menos dos usuarios, clientes y un administrador para llevar a cabo la revisión.

|**Clientes**||
| :- | :- |
|**Usuario**|**Contraseña**|
|clienteUno|123456|
|clienteDos|123456|

|**Cuidadores**||
| :- | :- |
|**Usuario**|**Contraseña**|
|cuidadorUno|123456|
|cuidadorDos|123456|

|**Administrador**||
| :- | :- |
|**Usuario**|**Contraseña**|
|admin|123456|

**La URL de la plataforma de despliegue:** [https://CuidaMe.appspot.com](https://cuidame.appspot.com)

**La URL de Github:** https://github.com/Galeon2098/CuidaME

**La URL y credenciales de la herramienta de seguimiento:** https://app.clockify.me/dashboard

- [**Bluejay**](http://dashboard.bluejay.governify.io/dashboard/script/dashboardLoader.js?dashboardURL=https://reporter.bluejay.governify.io/api/v4/dashboards/tpa-ISPP-2024-GH-Galeon2098_CuidaME/main)
- **Usuario**: user
- **Contraseña**: bluejay

Requisitos potenciales para usar el sistema: Ninguno de momento



## Mapeo de las interacciones de los casos de uso principales
### Registro como cuidador

Cuando accedemos a la página de inicio, deberemos dirigirnos a la parte superior derecha:

![ref1](./img/revision/1.png)

Una vez aquí, veremos la siguiente pantalla, donde encontraremos la opción para registrarnos como cuidador:
![](./img/revision/2.png)

Y ya nos enviaría al formulario de registro:
![](./img/revision/3.png)

Tras rellenar los campos y darle al botón de creación, ya habrás sido registrado como cuidador.

### Registro como cliente

Cuando accedemos a la página de inicio, deberemos dirigirnos a la parte superior derecha:

![ref1](./img/revision/1.png)

Una vez aquí, veremos la siguiente pantalla, donde encontraremos la opción para registrarse como cliente:

![](./img/revision/4.png)

Y ya nos enviaría al formulario de registro:
![](./img/revision/5.png)

Tras rellenar los campos y darle al botón de creación, ya habrás sido registrado como cuidador.

### Logueo como ambos usuarios

Bastaría con introducir los datos con los que nos hemos registrado anteriormente:
![](./img/revision/6.png)

Y nos enviaría a la página de inicio, que se vería tal que así:

![](./img/revision/7.png)

### Filtrado de cuidadores

Tendríamos que loguearnos como un cliente, pulsar en el botón “Offer list” y nos redirigirá a la siguiente página:

![ref2](./img/revision/8.png)

Posteriormente podremos filtrar por cualquiera de los campos que nos aparece. Por ejemplo, filtramos por tipo de cliente y ponermos el campo “Niños”.

![](./img/revision/9.png)

Una vez filtrado, nos aparecerían las ofertas que satisfagan el filtro.

### Solicitar chat a cuidador

Nos volvemos a loguear como cliente y, como en el caso de uso anterior, volvemos a acceder al apartado de la lista de ofertar:

![ref3](./img/revision/10.png)

Una vez que accedemos a esa página clicamos en ver detalle a la oferta del cuidador con el que queremos contactar:

![](./img/revision/11.png)

Una vez en los detalles de la ofertas, solicitamos el chat con el cuidador pulsando en el botón “Enviar Solicitud de Chat”.

![](./img/revision/12.png)

### Gestionar solicitudes de chat

Logueados como cuidadores nos dirigimos a “Solicitud de Chats”:

![](./img/revision/13.png)

En la siguiente pantalla nos aparecerá un registro de chats en la que podremos “Aceptar” o “Denegar” la solicitud de chat con los clientes.

![](./img/revision/14.png)

.
### Registro de chat

Logueados como cuidadores y al aceptar el chat con un cliente, accederíamos al chat con ellos, el cuál se vería así:

![](./img/revision/15.png)

La vista de cliente del chat sería igual pero sin el icono que nos redirecciona a la solicitudes de chat, ya que los clientes no tienen.

![](./img/revision/16.png)


### Administrar usuario
Nos logueamos como cliente o cuidador y accedemos a “Mi perfil”

![](./img/revision/17.png)

En la siguiente pantalla veremos nuestros datos como usuario de la aplicación. Para editarlos clicamos en “Editar Perfil”.

![](./img/revision/18.png)

A continuación, podremos editar nuestros datos y guardarlos dándole a “Actualizar”.

![](./img/revision/19.png)

Cabe recalcar que dependiendo si estamos logueados como clientes o cuidadores, podremos editar unos datos u otros.





### Publicar un anuncio

Nos logueamos como cuidadores y pulsamos sobre el botón “Mis ofertas”:

![](./img/revision/20.png)

Pulsamos sobre el botón de publicar una oferta:

![](./img/revision/21.png)






Y a continuación, rellenamos los campos de la oferta y pulsamos sobre el botón de “publicar”:

![](./img/revision/22.png)

Una vez relleno el formulario y pulsado sobre el botón de “publicar”, pasamos a una vista en la que salen todas nuestras ofertas publicadas, donde podemos acceder a editarlas, eliminarlas o crear otra oferta nueva:

![](./img/revision/23.png)



### Editar y borrar un anuncio

Nos logueamos como cuidadores y volvemos a acceder a la lista de ofertas clicando en “Listado de oferta”

![](./img/revision/24.png)

Pulsamos en el botón “Editar” de la oferta que queremos editar:

![](./img/revision/25.png)


Una vez aquí, ya podremos editar y eliminar nuestra oferta.

![](./img/revision/26.png)

### Valoración de un cuidador

Accedemos a la oferta siguiendo los pasos del caso de uso 5. Una vez dentro rellenamos la valoración y seleccionamos un número de estrellas. Por último, clicamos en “Añadir comentario”

![](./img/revision/27.png)
## Condiciones suficientes para el fallo del software
-Una interacción legal con su sistema resulta en un error HTTP percibido por el usuario.

-Una interacción legal con su sistema resulta en un pánico (crash/...) percibido por el usuario.

-Una interacción legal con su sistema no tiene el comportamiento esperado.

-Enviar un formulario con datos incorrectos no es detectado. (validación de formulario).

-Un actor puede listar, editar o eliminar datos que pertenecen a otro actor.

-El sistema no está desplegado en la nube o no está disponible en algún momento durante el tema (hasta julio).

-El despliegue del sistema es modificado/actualizado después de la fecha límite de entrega.

