# 💾 Herramientas y Tecnologías

**Autor(es):**
- Suárez García, Antonio José
- Vázquez Rodríguez, Fausto

|**Fecha**|**Versión**|
| :-: | :-: |
|03/02/2024|v1.0|
|05/02/2024|v1.1|
|10/02/2024|v1.2|
|19/02/2024|v1.3|
|04/03/2024|v.2.0|
|05/04/2024|v.3.0|
|22/04/2024|v.3.1|
|06/05/2024|v.3.2|


## Introducción
En este documento vamos a comentar el uso que se le ha dado a las distintas herramientas de coordinación del grupo. Dichas herramientas cumplen las tareas de comunicación, control de tiempo, gestión de versiones de código, presentaciones, wiki y mockups.

Además, se incluyen varias tablas para analizar las estadísticas de contenido o tiempo en aquellas herramientas que lo requieran.
## Resumen
### Herramientas del Equipo

|**ÁMBITO**|**HERRAMIENTA**|**ENLACE**|
| :-: | :-: | :-: |
|Comunicación|Whatsapp|-|
|Comunicación|Discord|https://discord.gg/fY5J4Jk4|
|Control del Tiempo|Clockify|https://app.clockify.me/es/login|
|Documentación|Google Drive|https://drive.google.com/drive/folders/10LXvqf9D517EPvv3yxgt7VAsoGj6ynkS?usp=sharing|
|Repositorio|GitHub (Código)|https://github.com/Galeon2098/CuidaME.git|
|Repositorio|GitHub (Documentación)|https://github.com/CuidaMe-Org/cuidaMe-docs|
|Presentaciones|Canva|https://www.canva.com/|
|Wiki del Grupo|Wikidot (Obsoleta)|http://cuidame.wikidot.com/|
|Wiki del Grupo|Docusaurus|https://cuida-me-docs-sigma.vercel.app/docs/grupo|
|Wiki de la Asignatura|Docusaurus|https://bgcc.vercel.app/|
|Mockups|Marvel App|https://marvelapp.com/prototype/7d58gha|
|Gestión de Proyectos|Github Project|-|
|Pruebas automáticas|Github Actions|-|

### Tecnologías

|**ÁMBITO**|**HERRAMIENTA**|**COMENTARIOS**|
| :-: | :-: | :-: |
|Control de Versiones|Git|Descargar en: https://git-scm.com/downloads|
|Entorno de Desarrollo|Visual Studio Code (Recomendado)|-|
|Lanzamiento de la Wiki del Grupo|Node.js|Descargar en: https://nodejs.org/en/download|
|Base de Datos|SQL|Por defecto en django. Usar extensión en VSCode: SQLite Viewer|
|Base de Datos|PostgreSQL|Usada en el despliegue. Descargar en: https://www.postgresql.org/download/|
|Back-end|Python|Versión: 3.10. Descargar en: https://www.python.org/downloads/|
|Back-end|Django|Versión: 4.1.1. Descargar con el comando: python -m pip install django==4.1.1|
|Front-end|CSS|-|
|Front-end|HTML|-|
|Landing Page|Wix|-|
|Análisis de Código|Codacy|En todas las pull requests|
|Análisis de Código|SonarCloud|En los pull request hacia develop y master|
|Análisis de Trabajo|BlueJ|-|

### Despliegues

|**DESPLIEGUE**|**ENLACE**|
| :-: | :-: |
|Despliegue Sprint 1|https://ispp-09-cuidame.oa.r.appspot.com|
|Despliegue Sprint 2|https://cuidamesprint2.ew.r.appspot.com|
|Despliegue Sprint 3 y sucesivos|https://cuidame-sprint3.ey.r.appspot.com|

## Aplicaciones Importantes
### Discord
**Ámbito y Utilidad**

Discord se presenta como una herramienta para establecer las comunicaciones online en el contexto del grupo. Cobra vital importancia ya que todas las reuniones de carácter formal tienen lugar en esta aplicación. Además, permite la transferencia de texto y archivos, facilitando el desarrollo de tareas simultáneas por varios miembros del equipo.

**Uso y Estructura**

Se crea un servidor con el nombre ISPP-G09, donde se encuentran todos los miembros del grupo. Se estructura en 7 módulos, siendo el primero uno de carácter general y los otros 6 orientados a los distintos subgrupos según los roles que existen: análisis, full stack, frontend, backend, testing y líderes de subgrupo. La participación por parte de los miembros en cada sección es libre, sin restricciones, por si en algún momento hace falta ayuda de alguien con otro rol. Esto hace que pese a existir dichos roles en la organización, no se plantean así en el servidor, ya que todos los miembros tienen los mismos permisos. Cada módulo posee de uno a varios canales de texto, con distintos propósitos indicados en el nombre, pero solo un único canal de voz.

**Ventajas**

- La herramienta es conocida por todos los miembros del grupo. 
- Para el contexto que se va a emplear con la versión gratuita es suficiente.
- Proporciona un servicio de comunicación por voz estable.
- Todos los miembros tenían la aplicación instalada, suponiendo un ahorro de tiempo.
- Permite también la transferencia de archivos.


### Clockify
**Ámbito y Utilidad**

Clockify se emplea para llevar un control exhaustivo del tiempo. Para ello cada miembro del grupo es responsable de contabilizar sus propias horas en el desarrollo de sus tareas. Esta aplicación tiene mucha importancia para llevar un registro apropiado de cara al cumplimiento de las 10 horas de trabajo semanal.

**Uso y Estructura**

Se crea un espacio de trabajo con el nombre ISPP-G09, donde se encuentran todos los miembros del grupo. Se establecen 6 tipos distintos de proyecto, pudiéndose asignar cualquiera de ellos a la tarea que se esté realizando. Estos tipos son: documentación, backend, frontend, clases, píldoras y reuniones. Cada miembro es responsable de contabilizar sus propias horas.

**Ventajas**

- Para el contexto que se va a emplear con la versión gratuita es suficiente.
- Miembros del equipo ya tenían experiencia en ella.
- Se valora su simpleza y facilidad de comprensión.
- Permite sacar estadísticas de forma cómoda.


### Google Drive
**Ámbito y Utilidad**

Google Drive proporciona un servicio perfecto para almacenar la documentación que se va generando en el proyecto. Cumple perfectamente su función como repositorio de ficheros, a la vez que facilita la tarea de localización y control de los documentos.

**Uso y Estructura**

Se crea una carpeta compartida por todos los miembros del equipo llamada ISPP. La estructura de subcarpetas y ficheros va evolucionando conforme lo hace el proyecto, haciendo que sea completamente dinámica. En esta aplicación se alojan tanto los documentos oficiales como los de apoyo: presentaciones, tablas, de evaluación… Todos los miembros tienen los mismos permisos: subida o bajada de ficheros, creación de carpetas, edición...

**Ventajas**

- Para el contexto que se va a emplear con la versión gratuita es suficiente.
- Creación y subida de ficheros con facilidad.
- Edición de documentos en tiempo real.
- Integración con el resto de servicios de google.
- Todos los miembros del grupo tienen conocimientos de la aplicación.
- Control de versiones en los documentos.


### GitHub
**Ámbito y Utilidad**

GitHub cubre las necesidades del grupo como repositorio de código software. Es una parte fundamental del proyecto, sobre todo en la etapa de desarrollo. Además de su función principal, proporciona otras de gran utilidad como: gestión de versiones, historial de commits, administración de ramas…

**Uso y Estructura**

Se crea un repositorio llamado CuidaME al que tienen acceso todos los miembros del grupo. Dichos miembros poseen los mismos permisos de administración y tienen la capacidad en cualquier momento tanto de editar el código, como de crear y eliminar ramas. También se llega al acuerdo de crear 6 milestones, uno por cada fase del proyecto: Devising a project (DP), Sprint 1 (S1), Sprint 2 (S2), Sprint 3 (S3), Preparing project launch (PPL) y World project launch (WPL). Además, para llevar una clasificación más óptima de las tareas se implementan 12 etiquetas, no excluyentes, en función de su propósito: Aceptada, Análisis, Backend, Bug, Documentación, Feedback, Frontend, Fullstack, Hotfix, Rechazada, Testing y Wiki. Por último, se hace uso de un tablero kanban llamado CuidaMe´s Project Board para tener un control visual del estado de las tareas. En él se establecen cuatro fases: To Do, In Progress, In Review y Done.

**Ventajas**

- Para el contexto que se va a emplear con la versión gratuita es suficiente.
- Todos los miembros del grupo estaban familiarizados con la herramienta.
- Posee herramientas auxiliares bastante útiles como GitHub Desktop.
- Proporciona un modo fácil de crear tableros kanban.
- Facilita la creación y gestión de ramas.
- Permite llevar un control de versiones.


### Docusaurus
**Ámbito y Utilidad**

Docusaurus se emplea como servicio web para la construcción de la wiki por parte del grupo de trabajo mediante la tecnología react. El espacio formado para el proyecto proporciona un control de la información básica a la vez que permite un acceso libre a cualquiera que lo deseara.

**Uso y Estructura**

Antes se usaban los servicios de Wikidot con una wiki creada llamada CuidaMe en el espacio cuidame.wikidot. El acceso era de carácter libre, pero la capacidad de edición y modificación se reservaba a unos pocos integrantes del grupo del proyecto. 

Actualmente se hace uso de Docusaurus. Para ello se tiene un repositorio donde está implementado toda la estructura del servicio y en el que se hallan los documentos más importantes, siguiendo el formato Markdown. Además, está desplegada de forma online para que sea accesible por cualquier persona que lo considere. La capacidad de edición y modificación la posee todos los miembros del equipo.

**Ventajas**

- Para el contexto que se va a emplear con la versión gratuita es suficiente.
- Permite llevar un control de la información por parte del grupo.
- La wiki creada es de acceso libre.
- Posee multitud de opciones de personalización.
- Permite mantener un formato común gracias al lenguaje Markdown.


### Otros
**WhatsApp**

Aplicación que permite una comunicación más cercana y relaja. Existe un grupo donde se encuentran todos los miembros del proyecto, lo cual facilita el procedimiento a la hora de transmitir cualquier noticia importante o en el momento de organizar a los participantes.

**Canva**

Es una herramienta que permite crear presentaciones más originales y creativas. Tiene una gran cantidad de accesorios que aumentan la calidad de la parte visual. Se eligió utilizarla aprovechando los conocimientos de unos pocos miembros del grupo.

**Marvel App**

Marvel App es un servicio que permite al equipo crear mockups de una forma fácil y completa. Además, añade opciones de interactividad en los bocetos creados. Se optó por su uso gracias al conocimiento previo de alguno de los implicados.


**Wix**

Para la creación de páginas estáticas de forma asistida. Utilizada para la creación de la Landing Page del proyecto.
## Estadísticas
### Reloj - Clockify
El reloj se usa como estadística para medir el tiempo invertido por cada miembro en una semana. Los datos son obtenidos de la herramienta de control de tiempo clockify, contabilizando las semanas desde el martes en el que se imparte la clase hasta el lunes siguiente. Cabe destacar que tiene un grado de precisión de minutos, y siempre se aproxima con un redondeo hacia arriba. Además se lleva el control tanto a nivel individual (contabilizando los incrementos y las horas restantes de trabajo), como colectivo

Reloj Individual (Horas Restantes):


|**Estudiante**|**Semana 0**|**Semana 1**|**Semana 2**|**Semana 3**|**Semana 4**|**Semana 5**|**Semana 6**|**Semana 7**|**Semana 8**|**Semana 9**|**Semana 10**|**Semana 11**|**Semana 12**|**Semana 13**|**Semana 14**|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|Abulatifa, Mohanad|140:00|132:38|119:26|111:15|97:39|86:26|78:51|61:22|60:49|55:31|41:20|32:44|23:19|14:34|-|
|Castellano Alonso, Álvaro|140:00|129:55|118:08|108:14|95:10|80:11|69:29|59:59|46:42|33:02|24:22|17:26|9:24|-0:30|-|
|De La Prada Prados, Francisco Javier|140:00|130:08|116:18|104:23|94:03|86:03|75:33|65:28|54:19|44:19|34:19|23:39|13:44|1:14|-|
|Del Río Pérez, Carlos|140:00|133:53|125:09|116:25|102:53|91:21|81:26|70:13|62:41|56:09|44:01|33:08|27:08|18:16|-|
|Diáñez Suárez, Daniel|140:00|131:50|116:33|108:11|96:39|82:18|72:00|66:53|54:44|43:07|34:08|23:50|14:20|0:37|-|
|García Galocha, Rafael David|140:00|131:19|120:38|110:19|100:09|85:04|73:20|64:19|53:36|42:50|32:22|23:20|16:41|6:41|-|
|García Hernández, Cristina|140:00|130:05|119:49|107:55|97:27|75:25|65:45|56:49|25:06|19:06|-06:19|-12:44|-13:19|-24:01|-|
|Granados López, Manuel J.|140:00|129:30|119:30|106:35|94:25|84:45|74:35|68:00|53:42|43:42|32:12|24:52|14:00|1:15|-|
|Jiménez Del Villar, Juan Antonio|140:00|132:15|127:33|114:27|102:21|89:59|81:21|75:13|63:17|53:02|22:01|14:44|5:11|1:11|-|
|León Madroñal, Juan Carlos|140:00|131:42|119:10|109:19|98:47|87:12|80:53|70:16|58:25|48:19|38:23|28:50|22:29|13:12|-|
|Márquez González, Diego|140:00|129:00|116:51|102:49|90:22|84:15|74:04|64:13|53:25|39:38|27:41|17:21|8:21|-1:10|-|
|Pérez Romero, Lucía|140:00|130:10|120:10|107:00|87:51|77:43|67:41|52:21|31:51|19:36|01:36|-04:24|-12:19|-17:42|-|
|Restoy Barrero, Joaquín|140:00|132:45|122:04|109:53|96:47|83:06|74:18|69:24|51:06|45:37|34:39|23:33|12:47|4:34|-|
|Suárez García, Antonio J.|140:00|136:00|134:00|118:24|107:05|85:45|79:17|75:04|60:07|48:48|33:28|29:04|18:00|9:26|-|
|Vázquez Rodríguez, Fausto|140:00|133:53|121:49|110:09|95:42|80:37|69:39|59:38|46:45|32:54|11:49|02:35|-14:57|-20:27|-|
|Vidal Tevar, Gabriel|140:00|136:00|127:39|118:31|109:18|100:58|94:58|85:46|66:29|66:29|58:15|57:45|52:52|9:08|-|

Reloj Individual (Horas Trabajadas):


|**Estudiante**|**Semana 0**|**Semana 1**|**Semana 2**|**Semana 3**|**Semana 4**|**Semana 5**|**Semana 6**|**Semana 7**|**Semana 8**|**Semana 9**|**Semana 10**|**Semana 11**|**Semana 12**|**Semana 13**|**Semana 14**|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|Abulatifa, Mohanad|0:00|7:22|13:13|8:12|13:36|11:13|7:35|17:29|0:33|5:18|14:11|8:36|9:25|8:45|-|
|Castellano Alonso, Álvaro|0:00|10:05|11:47|9:55|13:04|15:00|10:42|9:30|13:18|13:40|8:40|6:56|8:02|9:56|-|
|De La Prada Prados, Francisco Javier|0:00|9:52|13:50|11:55|10:20|8:00|10:30|10:05|11:09|10:00|10:00|10:40|9:55|12:30|-|
|Del Río Pérez, Carlos|0:00|6:07|8:45|8:44|13:33|11:33|9:56|11:13|7:32|6:33|12:08|10:54|6:00|8:52|-|
|Diáñez Suárez, Daniel|0:00|8:10|15:17|8:23|11:32|14:22|10:18|5:08|12:10|11:38|8:59|10:18|9:30|13:43|-|
|García Galocha, Rafael David|0:00|8:41|10:41|10:20|10:10|15:06|11:44|9:01|10:44|10:46|10:28|9:03|6:40|10:00|-|
|García Hernández, Cristina|0:00|9:55|10:16|11:54|10:28|22:02|9:41|8:57|31:43|6:00|25:27|6:25|0:35|10:43|-|
|Granados López, Manuel J.|0:00|10:30|10:00|12:55|12:10|9:40|10:10|6:35|14:18|10:00|11:30|7:20|10:52|12:45|-|
|Jiménez Del Villar, Juan Antonio|0:00|7:45|4:42|13:07|12:06|12:23|8:38|6:08|11:57|10:15|31:01|7:17|9:33|4:00|-|
|León Madroñal, Juan Carlos|0:00|8:18|12:32|9:52|10:32|11:36|6:19|10:38|11:52|10:07|9:56|9:34|6:21|9:18|-|
|Márquez González, Diego|0:00|11:00|12:10|14:02|12:28|6:08|10:11|9:52|10:49|13:47|11:57|10:20|9:00|9:32|-|
|Pérez Romero, Lucía|0:00|9:50|10:00|13:10|19:09|10:08|10:02|15:20|20:30|12:15|18:00|6:00|7:55|5:23|-|
|Restoy Barrero, Joaquín|0:00|7:15|10:41|12:11|13:06|13:42|8:49|4:54|18:18|5:30|10:58|11:06|10:47|8:14|-|
|Suárez García, Antonio J.|0:00|4:00|2:00|15:36|11:20|21:20|6:29|4:13|14:57|11:19|15:21|4:24|11:04|8:34|-|
|Vázquez Rodríguez, Fausto|0:00|6:07|12:04|11:40|14:28|15:05|10:58|10:02|12:53|13:52|21:06|9:14|17:34|5:30|-|
|Vidal Tevar, Gabriel|0:00|4:00|8:21|9:09|9:13|8:21|6:00|9:12|19:18|0:00|8:14|0:30|4:53|9:08|-|

Reloj Colectivo:


|**Métrica**|**Semana 0**|**Semana 1**|**Semana 2**|**Semana 3**|**Semana 4**|**Semana 5**|**Semana 6**|**Semana 7**|**Semana 8**|**Semana 9**|**Semana 10**|**Semana 11**|**Semana 12**|**Semana 13**|**Semana 14**|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|Media de horas realizadas|0:00|8:04|10:24|11:19|12:20|12:51|9:15|9:16|13:53|9:26|14:15|8:03|8:38|9:11|-|
|Media de horas realizadas (+10%)|0:00|8:52|11:26|12:27|13:34|14:08|10:11|10:12|15:16|10:23|15:40|8:51|9:30|10:06|-|
|Media de horas realizadas (+40%)|0:00|11:17|14:33|15:51|17:16|18:00|12:57|12:58|19:26|13:13|19:57|11:15|12:05|12:51|-|
|Media de horas realizadas (-10%)|0:00|7:16|9:21|10:11|11:06|11:34|8:20|8:21|12:30|8:30|12:50|7:14|7:46|8:16|-|
|Media de horas realizadas (-40%)|0:00|4:51|6:14|6:48|7:24|7:43|5:33|5:34|8:20|5:40|8:33|4:50|5:11|5:31|-|
|Decremento de horas totales|2240:00|2111:05|1944:54|1763:57|1566:47|1361:13|1213:18|1065:07|843:11|692:16|464:24|335:50|197:48|50:57|-|
|Decremento de horas esperado|2240:00|2080:00|1920:00|1760:00|1600:00|1440:00|1280:00|1120:00|960:00|800:00|640:00|480:00|320:00|160:00|0:00|
|Comparación entre horas totales y esperadas|Neutro|Negativo|Negativo|Negativo|Positivo|Positivo|Positivo|Positivo|Positivo|Positivo|Positivo|Positivo|Positivo|Positivo|-|


### Software - Git y GitHub
Para medir el trabajo realizado en el repositorio software del proyecto se emplearán las métricas de: número de líneas de código y el número de ficheros del propio proyecto. Aunque esto se puede conseguir con el uso de la propia plataforma de GitHub, se han empleado herramientas externas para facilitar el trabajo. En concreto la extensión VS Code Counter en el editor de código Visual Studio Code, aplicado sobre la rama de Master.

En la siguiente tabla se muestra el incremento que ha habido cada semana en las métricas mencionadas anteriormente:


|**Métrica**|**Semana 0**|**Semana 1**|**Semana 2**|**Semana 3**|**Semana 4**|**Semana 5**|**Semana 6**|**Semana 7**|**Semana 8**|**Semana 9**|**Semana 10**|**Semana 11**|**Semana 12**|**Semana 13**|**Semana 14**|**Total**|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|Líneas de Código|0|2|0|19071|-16323|1355|854|5|36320|0|3076|0|305|843|-|45508|
|Número de Ficheros|0|1|0|31|23|26|0|0|205|0|25|0|0|16|-|327|


Además, para medir el uso de los beneficios del repositorio de código se emplearán las métricas a nivel de grupo de: número de commits realizados; el número de ramas creadas; el número de incidencias (issues) creadas, cerradas y comentadas; y el número de pull requests, creadas y comentadas. Todas las herramientas que se emplean están presentes por defecto en GitHub, como: el seguimiento efectivo gracias al historial de commits, las secciones de issues o de pull requests y la observación de tareas en el tablero kanban.

En la siguiente tabla se muestra el incremento que ha habido cada semana en las métricas mencionadas anteriormente:


|**Métrica**|**Semana 0**|**Semana 1**|**Semana 2**|**Semana 3**|**Semana 4**|**Semana 5**|**Semana 6**|**Semana 7**|**Semana 8**|**Semana 9**|**Semana 10**|**Semana 11**|**Semana 12**|**Semana 13**|**Semana 14**|**Total**|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|Número de Commits|0|1|0|10|47|157|21|1|283|3|229|0|2|172|-|922|
|Número de Ramas|*|*|*|*|*|*|44|13|9|12|8|5|3|1|-|95|
|Número de Incidencias Creadas|0|0|18|21|26|26|15|24|8|36|5|16|4|3|-|202|
|Número de Incidencias Cerradas|*|*|*|*|*|*|74|21|13|-1|12|9|1|2|-|131|
|Número de Incidencias con Comentarios|*|*|*|*|*|*|45|14|9|17|4|8|1|2|-|100|
|Número Comentarios en Incidencias|*|*|*|*|*|*|80|47|22|35|4|10|4|14|-|225|
|Media de Comentarios por Incidencia|*|*|*|*|*|*|1.78|3.36|2.44|2.05|3.25|1.25|4.00|7.00|-|2.25|
|Número de Pull Requests|*|*|*|*|*|*|52|9|15|7|13|1|7|1|-|105|
|Número de Pull Requests con Comentarios|*|*|*|*|*|*|33|10|14|7|12|2|7|1|-|86|
|Número Comentarios en Pull Requests|*|*|*|*|*|*|87|28|68|16|65|3|32|4|-|303|
|Media de Comentarios por Pull Request|*|*|*|*|*|*|2.64|2.8|4.86|2.29|5.42|1.5|4.57|4.00|-|3.52|

- El color amarillo (*) significa que no se han recogio o no se van a recoger estadísticas en ese periódo.

### Documentos - Google Drive
Con el fin de llevar un control de los diversos ficheros, sobre todo documentos,  necesarios en el proyecto se ha hecho uso de Google Drive. La métrica principal que puede servir para resaltar el crecimiento del trabajo realizado es el número de archivos totales. Este último se calcula mediante un script existente en la hoja de cálculo llamada Contador de Documentos de Google Drive. Simplemente en la pestaña de extensiones pulsar en App Script y en la ventana emergente darle a la opción de ejecutar.

En la siguiente tabla se muestra el incremento que ha habido cada semana en las métricas mencionadas anteriormente:


|**Métrica**|**Semana 0**|**Semana 1**|**Semana 2**|**Semana 3**|**Semana 4**|**Semana 5**|**Semana 6**|**Semana 7**|**Semana 8**|**Semana 9**|**Semana 10**|**Semana 11**|**Semana 12**|**Semana 13**|**Semana 14**|**Total**|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|Número de Archivos|0|32|29|45|71|39|16|15|32|10|32|4|8|20|-|353|


### Comunicación - Discord
Para llevar una supervisión de las comunicaciones interpersonales se ha contabilizado el número de reuniones y las horas invertidas en ellas en la plataforma de Discord. Aunque cabe destacar que solo se ha tenido en cuenta las reuniones que son de carácter oficial, y por tanto poseen un acta.

En la siguiente tabla se muestra el incremento que ha habido cada semana en las métricas mencionadas anteriormente:



|**Métrica**|**Semana 0**|**Semana 1**|**Semana 2**|**Semana 3**|**Semana 4**|**Semana 5**|**Semana 6**|**Semana 7**|**Semana 8**|**Semana 9**|**Semana 10**|**Semana 11**|**Semana 12**|**Semana 13**|**Semana 14**|**Total**|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|Número de Reuniones|0|1|1|3|2|2|1|1|1|1|0|1|0|1|-|15|
|Tiempo de Reuniones|0:00|2:00|2:00|3:50|4:20|5:00|1:10|2:00|1:50|1:30|0|1:50|0|2:30|-|27:00|


Dado que no se prevé que cambie la estructura del servidor creado en Discord, las siguientes estadísticas se presuponen de carácter estático:



|**Discord**||
|:-:|:-:|
|Secciones|7|
|Canales de Texto|12|
|Canales de Voz|7|


### Información - Wikidot y Docusaurus
Cuando se hacía uso de Wikidot, con la intención de examinar la evolución de la wiki del proyecto se establece la métrica del número de páginas creadas. Para ello solo se tienen en cuenta aquellas construidas por el equipo de trabajo, y no las que vienen por defecto. Además, mediante la web histats se hace un seguimiento del número de visitas por semana, monitorizando así la afluencia en la página de la wiki. Los datos son obtenidos de la contabilizando las semanas desde el martes en el que se imparte la clase hasta el lunes siguiente.

Enlace a histats: https://www.histats.com/viewstats/?sid=4844287&act=2 

En la siguiente tabla se muestra el incremento que ha habido cada semana en las métricas  de Wikidot mencionadas anteriormente:


|**Métrica**|**Semana 0**|**Semana 1**|**Semana 2**|**Semana 3**|**Semana 4**|**Semana 5**|**Semana 6**|**Semana 7**|**Semana 8**|**Semana 9**|**Semana 10**|**Semana 11**|**Semana 12**|**Semana 13**|**Semana 14**|**Total**|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|Número de Páginas|0|0|10|7|2|1|*|*|*|*|*|*|*|*|*|20|
|Número de Visitas|0|0|105|360|214|61|*|*|*|*|*|*|*|*|*|740|

- El color amarillo (*) significa que no se han recogio o no se van a recoger estadísticas en ese periódo.


Cuando se pasa a Docusaurus, se establece únicamente la métrica del número de páginas creadas y el número de líneas. Para ello, aunque se puede conseguir con el uso de la propia plataforma, se han empleado herramientas externas para facilitar el trabajo. En concreto la extensión VS Code Counter en el editor de código Visual Studio Code, aplicado sobre la rama de main del repositorio de documentos. Solo se tienen en cuenta aquellas páginas construidas por el equipo de trabajo, y no las que vienen por defecto, por lo que solo se mira el número de ficheros Markdown de la subcarpeta docs. Los datos son obtenidos de la contabilizando las semanas desde el martes en el que se imparte la clase hasta el lunes siguiente.

En la siguiente tabla se muestra el incremento que ha habido cada semana en las métricas  de Docusaururs mencionadas anteriormente:


|**Métrica**|**Semana 0**|**Semana 1**|**Semana 2**|**Semana 3**|**Semana 4**|**Semana 5**|**Semana 6**|**Semana 7**|**Semana 8**|**Semana 9**|**Semana 10**|**Semana 11**|**Semana 12**|**Semana 13**|**Semana 14**|**Total**|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|Número de Páginas|*|*|*|*|*|*|72|0|12|0|16|1|18|0|-|119|
|Número de Líneas|*|*|*|*|*|*|4579|0|918|47|1961|165|1347|51|-|9068|

- El color amarillo (*) significa que no se han recogio o no se van a recoger estadísticas en ese periódo.


