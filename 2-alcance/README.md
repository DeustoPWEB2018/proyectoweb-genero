# PLANO DE ALCANCE

## INTRODUCCIÓN

## ESPECIFICACIONES FUNCIONALES
Las especificaciones funcionales hacen referencia al comportamiento de, en nuestro caso, una página web relacionada con la igualdad de género. La página web se llama Hoyportimañanapormi.com y en ella se encuentra contenido de todo tipo: noticias, reportajes, entrevistas, artículos, historias, consejos, etc.

## HOYPORTIMAÑANAPORMI.COM
> **Especificación Funcional**

> Petunia Flores

> *Última actualización: 4 de noviembre, 2018*
									
> **- CONFIDENCIAL -**

### 1. GENERALIDADES
*Hoyportimañanapormi.com* es un servicio, vía web, que ofrece contenido informativo y educativo sobre la igualdad de género. En el portal web se encontrarán noticias, reportajes, entrevistas, etc., y todas ellas relacionadas con la igualdad de género. 

El sitio web necesitará un usuario gestor de contenidos, es decir un usuario administrador que se encargará de actualizar todo el contenido de la página. Por otro lado, existirá un usuario voluntario que trata de aquellos usuarios que quieran formar parte de este proyecto y quieran proporcionar información interesante relacionada con la igualdad de género. Por supuesto esa información tendrá que pasar por la supervisión del usuario administrador; el cual decidirá añadir o no el contenido. Y finalmente, se encuentra el usuario no registrado que será aquel que entre al sitio web y que consuma nuestro contenido sin tener que registrarse. 

La pagina web estará divida en dos partes: la información estática (contacto, quiénes somos, log-in)  y la información dinámica (noticias, articulos, reportajes, entrevistas, historias reales, consejos).

### 2. ESCENARIOS
En este apartado crearemos ciertos escenarios supuestos donde imaginaremos el uso que le pueden dar nuestros usuarios a nuestro sitio web. A continuación se encuentran los siguientes escenarios:

#### 2.1. Escenario 1: Paula y su desconocimiento
Paula tiene 43 años, es directora informática de BOSCH Bilbao pero no todo es perfecto. Se encuentra dentro de una relación sentimental un tanto tóxica o eso empieza a sentir ella. No se atreve a hablar con su entorno sobre las situaciones que está viviendo con su actual pareja. Y como no tiene donde refugiarse decide sumergirse en Internet. En una de sus redes sociales (Facebook), allí encuentra una publicación que ha compartido una amiga suya y que trata sobre un sitio web donde tratan contenido relacionado con la igualdad de género; pero sobre todo es un lugar de refugio, ayuda y consejo. En consecuencia, Paula decide hacer clic en el enlace y entrar en hoyportimañanapormi.com. 

Paula encuentra un sitio web que muestra la realidad de la sociedad ante la igualdad de género, encuentra entrevistas con expertos (psicólogos, abogados) que tratan temas de violencia de género y sobre todo encuentra historias reales de otras mujeres que le hacen recapacitar que ella misma está viviendo una relación insana y que no puede permitirlo. Debido al impacto que tuvo para Paula este sitio web, decide ponerse en contacto con *hoyportimañanapormi.com* para pedir más información y para trasladarles su historia para que la publicasen con el objetivo de ayudar a otras personas como lo hicieron las historias de otras mujeres a ella. Por lo tanto, Paula es un usuario voluntario ya que se ha registrado en el sistema, cuenta con su propia cuenta y puede compartir contenido en la página web.

#### 2.2. Escenario 2: Juan y su trabajo para la universidad

#### 2.3. Escenario 3: Dolores y sus ganas de aprender

### 3. NO OBJETIVOS
Esta versión *no* incluirá las siguientes funciones:

* Compra de productos
* Suscripción de pago
* Publicación diraria de contenido
* Un lugar físico de contacto (oficina)
* Opción de consumir contenido únicamente estando registrado

### 4. DETALLES
#### 4.1. Requisitos funcionales de usuarios
Como se ha comentado en el anterior apartado, la página web dispondrá inicialmente de 3 perfiles de usuario distinto (usuario administrador, usuario voluntario y usuario no registrado), cada uno con requisitos funcinales específicos.

Así mismo, existirán 3 niveles jerarquicos: el primer nivel está formado por el usuario no registrado, el segundo nivel por el usuario voluntario y finalmente el tercer nivel por el usuario administrador del sitio web. Los usuarios de cada nivel tendrán asignadas sus funcionalidades pero también heredarán las de los niveles inferiores (el usuario administrador podrá acceder a las funcionalidades del voluntario y del no registrado; y el usuario voluntario podrá acceder a las del usuario no registrado). En la siguiente imagen se muestra la relación entre niveles. 

![Niveles de usuarios](/2-alcance/Niveles.png)

A continuación se presentan los requisitos de funcionamiento especificos de cada perfil de usuario.

#### 4.1.1. Usuario no registrado.
El usuario no registrado lo describiriamos como el visitante ocasional y dispondrá de los siguientes requisitos funcionales: 

  * **Acceso al contenido público:** este usuario tendrá acceso a todo el contenido que esté oficialmente publicado en el sitio web. No tendrá que registrarse para poder consumir nuestro contenido. Tendrá acceso a: noticias, reportajes, articulos, entrevistas, historias reales, consejos, quiénes somos y contacto.

  * **Registrarse:** tendrán la opción disponible para registrarse en *hoyportimañanapormi.com* opción para convertirse en un usuario voluntario. 


#### 4.1.2. Usuario voluntario (registrado)
El usuario registrado heredará las funcionalidades del usuario no registrado y dispondrá de nuevos requisitos funcionales:

  * **Registrarse:** deberan rellenar un formulario con los datos necesario y aceptar los términos legales sobre difusión y gestión de datos. 

  * **Autentificarse:** para poder acceder al contenido los usuarios voluntarios deberan hacer un log-in (usuario y contraseña).

  * **Realizar comentarios de mejoras y cambios:** la página web tendrá una funcionalidad para que los usuarios puedan realizar comentarios (privados) de mejoras o cambios en el contenido público. 

  * **Compartir información:** los usuarios voluntarios podrán compartir contenido relacionado con la igualdad de género. Para ello, tendrán una lugar específico donde poder adjuntar la información. 


#### 4.1.3. Usuario administrador
El usuario administrador heredará las funcionalidades disponibles para los iveles inferiroes de usuario de la página web, y además dispondrá de los siguinetes requisitos funcionales:

- **Gestor de contenido:**
  * **Agregar contenido**
  * **Editar contenido**
  * **Eliminar contenido**


- **Gestor de los perfiles registrados:**
  * **Gestión de perfiles:** el administrador, en el caso que sea necesario, podrá cambiar las funcionalidades concretas del usuario voluntario o incluso añadir nuevas.
  Gestión de la base de datos: el administrado del sitio web tiene acceso a la base de datos de los perfiles registrados. 

  * **Gestión del contenido adjuntado por el usuario voluntario:** el administrador será quien analice el contenido compartido por los usuarios voluntarios y también será quien decida qué contenido se publicará y cuál no. 

  * **Gestión de incidencias:** teniendo en cuenta que el administrador tiene acceso a la base de datos de los perfiles resgistrados, este gestionará posibles incidencias que ocurran durante el funcionamiento del sitio web (dar de baja usuarios, eliminar contenido, etc.).


- **Gestor de la configuración del sitio web:**
  * El **resto de tareas** relacionadas con el sitio web serán responsabilidad del usuario administrador: configuración de contenido, diseño, etc. 

## REQUERIMIENTOS DE CONTENIDOS

### Contenido
El contenido se divide en diferentes etapas:

#### Audiencia
Tras analizar las ventajas y desventajas de cada uno de los perfiles analizados anteriormente, es acertado considerar que adaptar la página web a una usuaria, __Dolores__ en este caso, que no tiene amplios conocimiento en lo que a navegación en la web se refiere será beneficioso para la accesibilidad del sitio web, puesto que aquellos usuarios avanzados en el mundo de Internet no tomarán por negativo un factor como tal, el que la interfaz y la navegación a través de la web sea sencilla, mientras que aquellos usuarios, como en este caso Dolores, que quieran disfrutar del contenido pero que no dispongan de un amplio conocimiento a la hora de navegar por la web, agradecerán que el sitio web sea accesible, lo que supondrá una ventaja, teniendo en cuenta que la ventaja competitiva reside en el contenido que se publicará en la web, y no tanto en el diseño o en la navegación.  

#### Mensaje
Dentro del sitio web, en el espacio dedicado a la publicación de los contenidos, el primer mensaje estará visible acompañada sobre una imagen descriptiva. El primer mensaje funcionará como hipervínculo en este caso. El segundo mensaje será el *lead* en el que se mostrará el resumen del texto, con las claves sobre las que se desarrollará el mismo. Viene a ser algo así como el resumen del contenido que se va a tratar en adelante. En caso de que los contenidos sean de otro tipo (vídeos o audios) será la descripción del mismo contenido. Se utilizarán palabras clave a modo de cumplir con las reglas *SEO* pero estas reglas no condicionarán el contenido del mismo.

En lo que al detalle se refiere, es resaltable que se le va a dedicar especial atención a los contenidos que figuren en el cuerpo de los textos publicados, siguiendo los principios del __contenido de consumo pausado__ o *Slow content*. Es por ello que se ofrecerán contenidos elaborados profundamente, siendo esta la innovación y el valor añadido del sitio web. En definitiva, el objetivo será ofrecer un contenido distinto al que los usuarios podrían encontrar en otro sitio web de similares características, de ahí que el punto de mira se centre en el contenido, principalmente, por encima del diseño.  

 
#### Temas

![Topic Map](https://github.com/DeustoPWEB2018/proyectoweb-genero/blob/HernandezArrizabalaga-alcance/2-alcance/topicmap.PNG)

#### Propósito
Principalmente, los propósitos a cumplir serán los siguientes:

* Educar: Uno de los principales propósitos es concienciar a las personas de la desigualdad existente en nuestra sociedad, además de educar acerca de cómo actuar ante este problema, a través de consejos a seguir y formas de actuar en determinadas situaciones

* Informar: En segundo lugar, informar acerca del tema en cuestión, dentro de las posibilidades existentes, partiendo de que tenemos límites en cuanto a alcance informativo y capacidad de creación de contenidos. Los contenidos elaborados deben ser puramente informativos, en ningún caso serán especulativos ni basados en rumores originarios de fuentes sin contrastar.
 
#### Tono y lenguaje
Teniendo en cuenta que la página web tratará principalmente el tema de la igualdad de género, así como temas más concretos relacionados con la violencia de género, deben tratarse estos temas con un lenguaje preciso, que no deje lugar a posibles interrogantes, y que trate con honor a las personas implicadas. Es por ello que debe respetarse siempre la presunción de inocencia y que no deben darse a conocer los datos de las personas que estén implicadas en estos tipos de actos, tanto los presuntos autores como las víctimas de esos actos. 

Por lo que al resto de contenidos respecta, nuestra postura como defensores y propulsores de la igualdad de género debe ser clara: Debemos mostrar un tono inclusivo, igualitario y equiditario para con la justicia en los contenidos que elaboraremos, alejándonos en todo momento de cualquier tipo de suspicacia, hipótesis infundada o sensacionalismo.

En cuanto al lenguaje y estilo de los contenidos, se debe buscar una forma de elaboración que no discrimine a los usuarios por la dificultad de comprensión del lenguaje, es decir, no debe utilizarse un lenguaje que se exceda en lo técnico, pero tampoco se deben utilizar formas de expresión demasiado coloquiales que pongan en duda el rigor de los informadores que trabajan los temas en cuestión. 

#### Fuentes
Hay un número de maneras de obtener contenidos para elaborar su estrategia de contenido:

* Contenido propio: Será la principal estrategia de creación de contenidos. Los contenidos escritos serán realizados a cargo del equipo de redacción. Por otro lado, en lo que se refiere a los contenidos de contenido audiovisual, serán creados por empleados de sus respectivas áreas. 

* Contenido co-creado: En determinados contenidos, se buscará el apoyo de distintos grupos o instituciones, que aporten datos o informes que puedan servir para tratar distintos temas. Partiendo del contenido creado por estas instituciones, se buscará elaborar contenidos más extensos, centrándose en un determinado aspecto del mismo que se completará con la colaboración de los redactores.   

* Contenido generado por el usuario: Los usuarios voluntarios (registrados) tendrán la posibilidad de compartir contenido creado por ellos mismos a través de un espacio destinado al mismo fin. Además de ello, también tendrán la posibilidad de realizar comentarios o sugerencias de mejora del sitio web.

#### Priorizar el contenido
Según Lee Thomas, es necesario seguir los siguientes criterios para priorizar el contenido:

* Requisitos: La decisión de ofrecer este tipo de contenidos a la sociedad es la necesidad de concienciar acerca del problema existente acerca de la desigualdad de género.

* Alcance: La audiencia se limitará a la población residente en Gipuzkoa, a pesar de que los contenidos propiamente pueden ser útiles o interesantes de leer para personas de habla hispana a las que les interese profundizar sus conocimientos acerca del tema.

* Relevancia: El valor ofrecido debe ser distinto para los usuarios que accedan a la página web. Un contenido que no encuentren en otro sitio web, basado en la profundidad y en un contenido que sea útil para ampliar conocimiento acerca del tema, tal y como hemos explicado anteriormente en el apartado de mensaje.

* Ingresos: Es evidente que existirá una retroalimentación entre el éxito obtenido a través de la audiencia del sitio web y las posibilidades de contratar anunciantes, así como la posibilidad de abarcar más temas, más conceptos y más hechos que interesen a nuestra audiencia. 


### REFERENCIAS

* Alsilla Morino, Joan. Diseño e implementación de un portal web para una empresa de sistemas de control de iluminación. Universitat Autònoma de Barcelona. 2009. Disponible online: https://ddd.uab.cat/pub/trerecpro/2010/hdl_2072_48072/AlsinaMorilloJoanR-ETISa2008-09.pdf
  
* Spolsky, Joel. Especificación funcional Quéhoraes.com. Disponible online: https://web.archive.org/web/20160604182621/http://spanish.joelonsoftware.com/PainlessSpecs/WhatTimeIsIt_Spanish.html 
