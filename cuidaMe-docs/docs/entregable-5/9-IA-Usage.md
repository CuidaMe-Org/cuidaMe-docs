# 🤖 Uso de la IA

**Autor(es):**
- De la Prada Prados, Francisco Javier
- Jiménez del Villar, Juan Antonio
- Granados López, Manuel Jesús


|**Fecha**|**Versión**|
| :-: | :-: |
|17/02/2024|v1.0|
|04/03/2024|v2.0|
|01/04/2024|v3.0|
|22/04/2024|v4.0|
|06/05/2024|v5.0|


## Presentación
En este documento vamos a comentar el uso que se le ha dado a la herramienta ChatGPT durante el transcurso de todo el proyecto. Dividiremos el documento en varias secciones, que corresponden a cada uno de los entregables a realizar seguido de tantas subsecciones como semanas de proyecto contenga dicho entregable.

Para describir cada uso de la IA se pondrá un título descriptivo de las consultas, una detallada descripción sobre la conversación y un enlace directo a la página de nuestra wiki (http://cuidame.wikidot.com) para poder visualizar de forma completa y detallada la conversación.

## Devising a project (#DP)
El entregable ha llevado desde la semana 2 a la semana 4 de proyecto. Se han realizado las siguientes consultas.
### Semana 2

- **Apoyo para la creación del documento “Commitment Agreement”**

  Se usó principalmente para la creación de los apartados del documento y para la posterior revisión para asegurarnos de utilizar un lenguaje correcto y formal.

La conversación completa puede verse desde aqui: http://cuidame.wikidot.com/acuerdo-ia

- **Generación de un eslogan**

  Diciéndole sobre que iba a tratar nuestra aplicación, se le solicitó un eslogan para la misma.

La conversación completa puede verse desde aquí: http://cuidame.wikidot.com/generacion-eslogan

### Semana 3

- **Creación del logo de nuestra aplicación**

  En primer lugar, se le solicita un logo moderno y minimalista para una aplicación para poner en contacto a personas dependientes o solitarias con potenciales cuidadores

  Tras generar un logo, se le solicita que lo rehaga utilizando la siguiente paleta de colores.

  ![Paleta de colores](./img/paleta_logo.png)

  Seguidamente, tras varias generaciones de logos  que no convencieron al equipo, se le pasa un logo genérico utilizado en la primera presentación del entregable el cuál era del agrado de todos los miembros.

  ![Logo prototipo](./img/logo_prototipo.png)

  Finalmente, con un par de generaciones más, fue capaz de generar el logo final.

  ![Logo final](./img/logo_final.png)

  La conversación completa puede verse desde aquí: http://cuidame.wikidot.com/creacion-del-logo



- **Solicitud de información de la competencia**

  Damos a la IA una descripción de los servicios que queremos ofrecer y pedimos información sobre empresas que puedan ofrecer esos mismos servicios en nuestro territorio de acción (España).

  La IA nos da esa información y le solicitamos información más precisa de nuestro competidor más directo (su DAFO, cómo competir contra ellos, las tecnologías que usan y en qué partes del territorio tienen mayor presencia.

  La conversación completa puede verse aquí:

  http://cuidame.wikidot.com/estudio-de-competidores

- **Asistencia para la generación de estrategias**

  Recopilando información sobre cómo realizar una análisis dafo correctamente, observamos que se mencionaba también la posibilidad de realizar estrategias para prepararnos para las distintas situaciones que se podrían dar en referente a nuestro dafo.

  Así que, pasando nuestro análisis dafo se le solicitó que hiciera estrategias ofensivas (fortaleza + oportunidad), defensivas (amenaza + fortaleza), adaptativas (debilidad + oportunidad) y de supervivencia (debilidad + amenaza).

  La conversación completa puede verse desde aquí: http://cuidame.wikidot.com/estrategias

- **Solicitud de tecnología FrontEnd para la aplicación**

  El equipo de FrontEnd del proyecto dudaba entre dos tecnologías posibles (Bootstrap o React) para el desarrollo de toda la interfaz de usuario de la aplicación.

  Se le consulta a la IA qué herramientas nos recomienda para desarrollar una PWA (progressive web app) recomendando, entre muchas, el uso de React.

  Posteriormente, gracias al feedback recibido en clases sobre la posibilidad de utilizar ambas tecnologías en nuestro desarrollo se le cuestionó sobre esto a ChatGPT comentanos que era posible y cómo hacerlo.

  Se decide en un principio optar por el uso único de React, después de consultar sobre la compatibilidad de todo el entorno de desarrollo con Windows 11 para ver si en conjunto era viable.

  Al llegar al comienzo del sprint 1 se empieza con el uso de react como herramienta de desarrollo frontend. Dada la poca experiencia del equipo con esta tecnología la dificultad en la realización del trabajo aumenta significativamente y el cumplimiento de los plazos parece más inalcanzable. En este contexto se decide abandonar de forma unánime react y usar Bootstrap.

  Todo lo ocurrido al llegar al sprint 1 nos demuestra que el uso de la IA sin una supervisión adecuada puede dar resultados contraproducentes. En este caso, se olvidó mencionar la poca experiencia del equipo con react.

  La conversación completa puede verse desde aquí: http://cuidame.wikidot.com/ia-frontend

### Semana 4

- **Ideas brainstorming innovación tecnológica**

  Era necesaria para la aplicación una innovación tecnológica que nos diferenciara claramente de nuestros competidores por lo que se solicitaron a ChatGPT dando contexto sobre la temática de la aplicación.

  Tras varias propuestas de gran complejidad generadas se le pide que las innovaciones recomendadas sean de mayor simpleza, ofreciéndonos varias innovaciones más ajustadas a lo solicitado.

  La conversación completa puede verse aquí:

  http://cuidame.wikidot.com/innovacion-tecnologica



### Semana 5

- **Base para la reorganización del feedback**

  Se le pide a ChatGPT que reorganice las 3 secciones en las que el grupo organiza el feedback en la base de datos común de los grupos de ISPP. Se le proporciona además todo el feedback recogido para que pueda plantear mejor las secciones solicitadas.

  Tras esto, ChatGPT mantiene las 3 secciones originales pero les añade 3 subsecciones a cada una de ellas para mejorar la organización de estas.

  La conversación completa puede verse aquí:

  https://chat.openai.com/share/71fda9e6-fd1c-42d4-9300-9d993b982ab7

- **Resolución de errores en el código**

  Se le pasa a ChatGPT los errores mostrados por la consola de Django para poder corregirlos y así tener un correcto funcionamiento en la aplicación. Tras un intercambio de mensajes y varias modificaciones en el código sugeridas por la IA, se consiguen solucionar los errores.

  La conversación completa puede verse aquí:

  https://chat.openai.com/share/521624e3-3722-47e5-85ab-711f27f8b031

- **Test para la definición de ofertas**

  Se le pide a ChatGPT que genere una serie de test para probar todas las funcionalidades necesarias de las ofertas, realizadas en nuestra aplicación.

  La conversación completa puede verse aquí:

  https://chat.openai.com/share/a0e3a12b-af5b-461b-b5ba-07c3104653fc



- Lucía Pérez Romero. Definición de hecho para el documento de evaluación de desempeño

  https://chat.openai.com/share/52bf28e4-9d6a-4f90-9ec8-5101b443d444

- Lucía Pérez Romero. Consulta de errores de código:

  https://chat.openai.com/share/521624e3-3722-47e5-85ab-711f27f8b031


## Sprint 2(#SP2)

### Semana 8

- **Elaboración Acuerdo de testing con el grupo de la mañana**

  La conversación completa puede verse aquí:

  https://chat.openai.com/c/161c3ee7-5407-402d-8207-caa856c5411b

- **Tarea de login con Facebook**

  Se pregunta una duda a ChatGPT sobre qué URL poner en la api de Facebook para iniciar sesión.

  La conversación completa puede verse aquí:

  https://chat.openai.com/share/d831021d-7a59-4081-966c-7f234abc98ca

  https://chat.openai.com/share/7019342e-f1e6-4691-a120-6a57660f2b67

### Semana 9

- **Elaboración del Customer Agreement**

  Se le pide elaborar un texto para la aceptación de Términos de Uso sobre el contexto de nuestro servicio.

  La conversación completa puede verse aquí:

  https://chat.openai.com/share/f52a0920-7cf4-4ab3-8403-ac0a814b65bf

- **Resolución de fallos**

  Mediante los registros de errores que mostraba la aplicación, se le pregunta a ChatGPT la resolución de estos.

  La conversación completa puede verse aquí:

  https://chat.openai.com/share/cd6ccf9a-113e-49ee-908e-02c1c75082ab

  https://chat.openai.com/share/82b8f6ea-a1e9-4d95-8045-ca1a3743c2cc

  https://chat.openai.com/share/bb3d665b-f9a7-457b-b1d6-ebdf3ebda9c0

- **Traducción política de privacidad**

  Se traduce el HTML proporcionado a español.

  La conversación completa puede verse aquí:

  https://chat.openai.com/share/c8bc3e43-de83-4dec-b8be-73cd67a70993


## Sprint 3 (#SP3)

### Semana 10

- **Elaboración de informes**
  
  Se le pide elaborar una plantilla/guía para la elaboración del informe de marketing en particular.

  La conversación completa puede verse aquí:

  https://chat.openai.com/share/d6a72406-ae65-405a-9861-fbc9bcd1c64e


### Semana 11

- **Creación del anuncio**

  Se utiliza la IA de creación de videos “raw shorts” para la creación de un anuncio de cara a la presentación.

  No hay registros de chat.

- **Corrección de fallos de sonarcloud**

  Se le pide ayuda sobre los distintos tipos de errores y fallos que teníamos en sonarcloud.

  La conversación completa puede verse aquí:

  https://chat.openai.com/share/758f6ec3-2d11-49a7-850e-127daecd21f2


### Semana 12

- **Creación del documento GDPR**

  Se utiliza la IA para la elaboración de correos con texto profesional en base a las circunstancias descritas.

  La conversación completa puede verse aquí:
  
  https://chatgpt.com/c/8b06bea7-740d-4d16-ab39-36dcc8e39c43


### Semana 13

- **Creación de anuncio para inversores**

  Se genera el anuncio para inversores con las características y contenido que se le describe.

  Herramienta usada:

  https://www.renderforest.com/es/

## Huella de carbono

Según ChatGPT, este consume una media de 0,2g de CO2 por pregunta. Por lo tanto viendo cuantas preguntas hemos hecho podemos tener una estimación de nuestra huella de carbono en el uso de la I.A.

Hemos realizado aproximadamente 131 preguntas, por lo tanto:
135*0,2 = 27g

No existe información fiable acerca de la huella de carbono de “raw shorts”, esto se debe a que puede variar debido a varios factores como la carga de trabajo de la propia IA, la densidad de la pregunta, si es bajo una licencia de pago o gratuita (destinando más recursos la comercializadora a las consultas de los clientes de pago), etc...








