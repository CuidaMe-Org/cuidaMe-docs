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
|cliente1|123456|
|cliente2|123456|

|**Cuidadores**||
| :- | :- |
|**Usuario**|**Contraseña**|
|cuidador1|123456|
|cuidador2|123456|

|**Administrador**||
| :- | :- |
|**Usuario**|**Contraseña**|
|admin|123456|

**La URL de la plataforma de despliegue:** [https://CuidaMe.appspot.com](https://cuidame.appspot.com)

**La URL de Github:** https://github.com/Galeon2098/CuidaME

**La URL y credenciales de la herramienta de seguimiento:https://app.clockify.me/dashboard** 

- [Bluejay](http://dashboard.bluejay.governify.io/dashboard/script/dashboardLoader.js?dashboardURL=https://reporter.bluejay.governify.io/api/v4/dashboards/tpa-ISPP-2024-GH-Galeon2098_CuidaME/main)
- **Usuario**: user
- **Contraseña**: bluejay

Requisitos potenciales para usar el sistema: Ninguno de momento



## Mapeo de las interacciones de los casos de uso principales
1. ### Registro como cuidador

Cuando accedemos a la página de inicio, deberemos dirigirnos a la parte superior derecha:

![ref1](./img/revision/Aspose.Words.0b08c53e-6334-4db4-b56b-ea73936c59e3.002.png)

Una vez aquí, veremos la siguiente pantalla, donde encontraremos la opción para registrarnos como cuidador:
![](./img/revision/Aspose.Words.0b08c53e-6334-4db4-b56b-ea73936c59e3.003.png)

Y ya nos enviaría al formulario de registro:
![](./img/revision/Aspose.Words.0b08c53e-6334-4db4-b56b-ea73936c59e3.004.png)

Tras rellenar los campos y darle al botón de creación, ya habrás sido registrado como cuidador.

2. ### Registro como cliente

Cuando accedemos a la página de inicio, deberemos dirigirnos a la parte superior derecha:

![ref1](./img/revision/Aspose.Words.0b08c53e-6334-4db4-b56b-ea73936c59e3.002.png)

Una vez aquí, veremos la siguiente pantalla, donde encontraremos la opción para registrarse como cliente:

![](./img/revision/Aspose.Words.0b08c53e-6334-4db4-b56b-ea73936c59e3.005.png)

Y ya nos enviaría al formulario de registro:
![](./img/revision/Aspose.Words.0b08c53e-6334-4db4-b56b-ea73936c59e3.006.png)

Tras rellenar los campos y darle al botón de creación, ya habrás sido registrado como cuidador.

3. ### Logueo como ambos usuarios

Bastaría con introducir los datos con los que nos hemos registrado anteriormente:
![](./img/revision/Aspose.Words.0b08c53e-6334-4db4-b56b-ea73936c59e3.007.png)

Y nos enviaría a la página de inicio, que se vería tal que así:

![](./img/revision/Aspose.Words.0b08c53e-6334-4db4-b56b-ea73936c59e3.008.png)

4. ### Filtrado de cuidadores

Tendríamos que loguearnos como un cliente, pulsar en el botón “Offer list” y nos redirigirá a la siguiente página:

![ref2](./img/revision/Aspose.Words.0b08c53e-6334-4db4-b56b-ea73936c59e3.009.png)

Posteriormente podremos filtrar por cualquiera de los campos que nos aparece. Por ejemplo, filtramos por tipo de cliente y ponermos el campo “Niños”.

![](./img/revision/Aspose.Words.0b08c53e-6334-4db4-b56b-ea73936c59e3.010.png)

Una vez filtrado, nos aparecerían las ofertas que satisfagan el filtro.

5. ### Solicitar chat a cuidador

Nos volvemos a loguear como cliente y, como en el caso de uso anterior, volvemos a acceder al apartado de la lista de ofertar:

![]./img/revision/Aspose.Words.0b08c53e-6334-4db4-b56b-ea73936c59e3.011.png

Una vez que accedemos a esa página clicamos en ver detalle a la oferta del cuidador con el que queremos contactar:

![](./img/revision/Aspose.Words.0b08c53e-6334-4db4-b56b-ea73936c59e3.012.png)

Una vez en los detalles de la ofertas, solicitamos el chat con el cuidador pulsando en el botón “Enviar Solicitud de Chat”.

![](./img/revision/Aspose.Words.0b08c53e-6334-4db4-b56b-ea73936c59e3.013.png)

6. ### Gestionar solicitudes de chat

Logueados como cuidadores nos dirigimos a “Solicitud de Chats”:

![](./img/revision/Aspose.Words.0b08c53e-6334-4db4-b56b-ea73936c59e3.014.png)

En la siguiente pantalla nos aparecerá un registro de chats en la que podremos “Aceptar” o “Denegar” la solicitud de chat con los clientes.

![](./img/revision/Aspose.Words.0b08c53e-6334-4db4-b56b-ea73936c59e3.015.png)

.
7. ## Registro de chat

Logueados como cuidadores y al aceptar el chat con un cliente, accederíamos al chat con ellos, el cuál se vería así:

![](./img/revision/Aspose.Words.0b08c53e-6334-4db4-b56b-ea73936c59e3.016.png)

La vista de cliente del chat sería igual pero sin el icono que nos redirecciona a la solicitudes de chat, ya que los clientes no tienen.

![](./img/revision/Aspose.Words.0b08c53e-6334-4db4-b56b-ea73936c59e3.017.png)


8. ### Administrar usuario
Nos logueamos como cliente o cuidador y accedemos a “Mi perfil”

![](./img/revision/Aspose.Words.0b08c53e-6334-4db4-b56b-ea73936c59e3.018.png)

En la siguiente pantalla veremos nuestros datos como usuario de la aplicación. Para editarlos clicamos en “Editar Perfil”.

![](./img/revision/Aspose.Words.0b08c53e-6334-4db4-b56b-ea73936c59e3.019.png)

A continuación, podremos editar nuestros datos y guardarlos dándole a “Actualizar”.

![](./img/revision/Aspose.Words.0b08c53e-6334-4db4-b56b-ea73936c59e3.020.png)

Cabe recalcar que dependiendo si estamos logueados como clientes o cuidadores, podremos editar unos datos u otros.





9. ### Publicar un anuncio

Nos logueamos como cuidadores y pulsamos sobre el botón “Mis ofertas”:

![](./img/revision/Aspose.Words.0b08c53e-6334-4db4-b56b-ea73936c59e3.021.png)

Pulsamos sobre el botón de publicar una oferta:

![](./img/revision/Aspose.Words.0b08c53e-6334-4db4-b56b-ea73936c59e3.022.png)






Y a continuación, rellenamos los campos de la oferta y pulsamos sobre el botón de “publicar”:

![](./img/revision/Aspose.Words.0b08c53e-6334-4db4-b56b-ea73936c59e3.023.png)

Una vez relleno el formulario y pulsado sobre el botón de “publicar”, pasamos a una vista en la que salen todas nuestras ofertas publicadas, donde podemos acceder a editarlas, eliminarlas o crear otra oferta nueva:

![](./img/revision/Aspose.Words.0b08c53e-6334-4db4-b56b-ea73936c59e3.024.png)



10. ### Editar y borrar un anuncio

Nos logueamos como cuidadores y volvemos a acceder a la lista de ofertas clicando en “Listado de oferta”

![](./img/revision/Aspose.Words.0b08c53e-6334-4db4-b56b-ea73936c59e3.025.png)

Pulsamos en el botón “Editar” de la oferta que queremos editar:

![](./img/revision/Aspose.Words.0b08c53e-6334-4db4-b56b-ea73936c59e3.026.png)


Una vez aquí, ya podremos editar y eliminar nuestra oferta.

![](./img/revision/Aspose.Words.0b08c53e-6334-4db4-b56b-ea73936c59e3.027.png)

11. ### Valoración de un cuidador

Accedemos a la oferta siguiendo los pasos del caso de uso 5. Una vez dentro rellenamos la valoración y seleccionamos un número de estrellas. Por último, clicamos en “Añadir comentario”

![](./img/revision/Aspose.Words.0b08c53e-6334-4db4-b56b-ea73936c59e3.028.png)

## Condiciones suficientes para el fallo del software
-Una interacción legal con su sistema resulta en un error HTTP percibido por el usuario.

-Una interacción legal con su sistema resulta en un pánico (crash/...) percibido por el usuario.

-Una interacción legal con su sistema no tiene el comportamiento esperado.

-Enviar un formulario con datos incorrectos no es detectado. (validación de formulario).

-Un actor puede listar, editar o eliminar datos que pertenecen a otro actor.

-El sistema no está desplegado en la nube o no está disponible en algún momento durante el tema (hasta julio).

-El despliegue del sistema es modificado/actualizado después de la fecha límite de entrega.


