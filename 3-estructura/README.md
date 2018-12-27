# PLANO DE ESTRUCTURA 

## DISEÑO DE LA INTERACCIÓN

**HOYPOTIMAÑANAPORMI.COM** es una página web relacionado con la igualdad de género. En este sitio web los usuarios van a poder acceder e interactuar de diversas formas y  a continuación se detallan.  

**1.	ACCEDER**

Primeramente, se encuentra el usuario que no se ha registrado en la página web. Este usuario tendrá opción de acceder y visualizar toda la información y contenido público. En el sitio web, encontrará diferentes secciones (noticias, artículos, reportajes, entrevistas historias reales, consejos, quiénes somos y contacto) y también tendrán la  opción de registrarse y opción de log in. 

**2.	REGISTRARSE**

Por otro lado, se encuentra el usuario que accede a la página web y por primera vez quiere registrarse. Para ello, accederá a la opción “regístrate” donde accede a un formulario. El formulario contiene las siguientes cuestiones:

-	Usuario
-	Fecha de nacimiento
-	Lugar de residencia
-	Sexo
-	Email  (de recuperación de contraseña)
-	Contraseña

Una vez que el usuario haya rellenado los datos correspondientes, acepta la acción y aparecerá la opción de “log in” donde deberá volver a añadir lo siguiente:

-	Usuario
-	Contraseña

Después de hacer log in, el usuario tendrá opción de visualizar todo el contenido de la página web y también tendrá una opción donde podrá adjuntar contenido interesante que tenga intención de publicar en la página web (decisión final del administrador). La pestaña se llama “adjunta tus propuestas”.

**3.	LOG IN**

En la página principal se encuentra la opción “Log in”, a está opción accederán aquellos usuarios previamente registrados donde deberán introducir lo siguiente:
-	Usuario
-	Contraseña

Cabe la posibilidad que el usuario en cuestión, no recuerde la contraseña, por ello tendrá la siguiente opción:
-	He olvidado mi contraseña

Cuando el usuario seleccione la opción “He olvidado mi contraseña” tendrá que introducir cuál es el correo de recuperación que en su día introdujo en el registro. 

-	Introducir email de recuperación

Inmediatamente una nueva contraseña se enviará al correo electrónico y en el propio mensaje encontrará un enlace directo a la página “Recuperación de contraseña”:

-	Usuario
-	Contraseña de recuperación

Una vez dentro, el usuario tendrá opción de acceder a todo el contenido publicado incluida a la opción llamada “Adjunta tus propuestas”, opción únicamente disponible para aquellos usuarios registrados. El resto no tendrán esa opción. 


**Adjunta tus propuestas**

Dentro de la opción adjunta tus propuestas se encuentran diferentes secciones:

- **Adjuntar:** la opción adjuntar permite adjuntar archivos de tipo PDF, Word, MP3, MPG y cuando se selecciona la opción “adjuntar” se podrá  buscar el archivo dentro del PC de cada usuario para poder subirlo al sitio web.

- **Tus propuestas:** en el apartado “tus propuestas” se encuentran todas las propuestas adjuntadas en orden cronológico. Únicamente podrá visualizar el contenido el propio usuario autor de las propuestas y el administrador que será quien haga la valoración final de publicar o no el contenido. 

- **Publicaciones:** finalmente se encuentra el apartado de publicaciones donde se encuentran, también ordenadas cronológicamente todas las propuestas finalmente publicadas. 

## ARQUITECTURA DE LA INFORMACIÓN

### CARD SORTING

Para comprobar u obtener una visión subjetiva y diferente a la organización de los contenidos que se encuentran en nuestro sitio web, se va a optar por realizar un test denominado Card sorting, en el que se cuestionará a un determinado número de personas acerca de la organización de los contenidos del sitio web,  con el objetivo de mejorar la accesibilidad al mismo, facilitando así la navegación del usuario, que en definitiva es uno de los aspectos más importantes que deben tenerse en cuenta a la hora de realizar el diseño de la estructura de nuestro sitio web.   

Se realizará un open card sorting cuyo objetivo consistirá en conocer el nivel de exactitud que hemos obtenido a la hora de nombrar los distintos contenidos que se publicarán en el sitio web, de tal forma que, se podrá comprobar la pertinencia de utilizar un determinado número de etiquetas, en base a las respuestas que se obtengan de los propios usuarios. 

A su vez, se ha decidido realizar la prueba sobre los contenidos que pertenecen a la información dinámica del sitio web, puesto que son las categorías sobre las cuáles se van a realizar más modificaciones. La prueba se ha realizado a cuatro individuos, que han realizado la misma por parejas. 

La tabla situada en la parte inferior muestra los resultados que se obtuvieron en la prueba del card sorting, de forma que la respuesta de cada pareja de usuarios se contabiliza a través de un voto. 

![clasificacion](/3-estructura/clasificacion.png)

En la prueba, los encuestados han agrupado dichos contenidos en un total de 10 grupos, siendo estos los siguientes: 

* Reportajes personas
* Profesionales
* Temas de Actualidad
* Información
* Eventos Noticiosos
* Entrevistas
* Noticias
* Reportajes
* Consejos
* Casos Reales 

Se ha optado por suprimir las categorías ”Temas de Actualidad” y “Reportajes de Personas” para incluirlas en “Noticias” y “Reportajes” dado el significado al que hacen referencia con esas palabras.  

Antes de comenzar con el análisis de los resultados, cabe destacar que las características geográficas de los individuos que realizaron la prueba no eran las mismas en los cuatro casos, de ahí que cabe la posibilidad de que aquellos individuos no residentes en el País Vasco, le otorguen un diferente significado a una determinada cuestión, de ahí que es necesario interpretar los resultados obtenidos partiendo de la diferencia cultural existente en este caso. 

Hemos observado que han existido discrepancias notorias en los resultados obtenidos, siendo las más destacadas los que se han producido en la categoría de reportajes. El criterio empleado para titular los contenidos de los reportajes partía sobre la base de elaborar un enunciado llamativo que tratase de una cuestión en particular. Se eliminaron las citas parafraseadas de expertos en este caso para incluirlos en la sección de entrevistas, con el objetivo de realizar una clara diferenciación en la misma. A pesar de ello, se han producido notorias discrepancias, lo que ha producido que los reportajes se hayan considerado a su vez: “Noticias”, “Entrevistas”, “Casos Reales” e “Información”.
 
Principalmente ha existido una clara discrepancia entre las secciones de “Reportaje”, “Entrevistas” y “Noticias”, lo cual nos indica que, cuando llegue el momento de incluir los contenidos en su respectiva categoría, deberíamos acompañarlos por un subtítulo que se emplee a modo de enunciado, o que indique la sección a la que hace referencia, para no dar lugar a equívocos. 

Tras ello, hemos decidido que el contenido de nuestro sitio web se clasificará a través de estas etiquetas:  

* Artículos
* Consejos
* Entrevistas
* Historias Reales 
* Noticias
* Reportajes

### CLASIFICAR EL CONTENIDO 
Tras la realización del cardsorting y en vista de los resultados obtenidos, hemos llegado a diferentes conclusiones:
Por un lado, en lo que a esquemas organizativos se refiere, tenemos claro que utilizaremos un esquema ambiguo o subjetivo. Nuestra página web va a ser de actualización continua. Es decir, los contenidos van a ir actualizándose de forma periódica, por lo que no tiene sentido implantar un esquema exacto y no dinámico. Concretamente, será un esquema de contenido por formato, siendo estos los especificados en el apartado anterior: Artículos, Consejos, entrevistas, historias reales, noticias y reportajes. 

Somos conscientes de que este tipo de esquema es más complicado de administrar, teniendo en cuenta que la manera en la que se clasifican las noticias puede ser distinta dependiendo de las personas. El ejemplo más claro es lo que ocurrió en el card sorting entre los alumnos locales y extranjeros.

En cuanto a la estructura organizativa de nuestra página web, utilizaremos un modelo de base de datos. Es decir, tenemos el contenido antes de tener nuestra estructura hecha, por lo que la estructura será claramente de abajo arriba.
Todo ello llega impuesto en cierta medida también por los diferentes ámbitos en los que nos movemos (radio, audiovisual, prensa escrita, etc.), que son nuestra fuente de contenido principal y la base desde la que parte todo.

Aún así, trataremos que desde que nuestra audiencia entre a nuestra página web, hasta el momento que encuentre lo que ha venido a buscar, el número de clicks sea el mínimo.

## DIAGRAMACIÓN

A la hora de realizar los diagramas es conveniente crear cuatro dependiendo del usuario y de la forma en la que accederán a la web.

Primero hemos creado un diagrama general donde el usuario deberá especificar que tipo de usuario es, ya que existen tres formas de acceder y por lo tanto tres tipos de usuarios:

![Diagrama de flujo general](/3-estructura/General.png) 

**1.	Acceder:** son aquellos usuarios que no tienen cuenta y tienen un acceso restringido ya que no podrán de todas las opciones que ofrece la web.

![Diagrama de flujo acceder](/3-estructura/Acceder.png)

**2.	Log in:** son aquellos usuario que ya se han registrado previamente y por lo tanto tienen acceso a todos los servicios que ofrecemos. 

![Diagrama de flujo log in](/3-estructura/Login.png)

**3.	Registrarse:** son aquellos usuarios que deciden unirse a nuestra web por primera vez y una vez registrados podrán obtener su log in y tener un acceso ilimitado al contenido de la web. 




