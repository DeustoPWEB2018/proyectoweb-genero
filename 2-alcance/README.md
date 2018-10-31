# PLANO DE ALCANCE

## INTRODUCCIÓN



## ESPECIFICACIONES FUNCIONALES
Las especificaciones funcionales hacen referencia al comportamiento de, en nuestro caso, una página web relacionada con la igualdad de género. La página web se llama Hoyportimañanapormi.com y en ella se encuentra contenido de todo tipo: noticias, reportajes, entrevistas, artículos, historias, consejos, etc.

								HOYPORTIMAÑANAPORMI.COM
								Especificación Funcional

									Petunia Flores
						Última actualización: 4 de noviembre, 2018
									
									- CONFIDENCIAL -
### 1. Generalidades
*Hoyportimañanapormi.com* es un servicio, vía web, que ofrece contenido informativo y educativo sobre la igualdad de género. En el portal web se encontrarán noticias, reportajes, entrevistas, etc., y todas ellas relacionadas con la igualdad de género. 

El sitio web necesitará un usuario gestor de contenidos, es decir un usuario administrador que se encargará de actualizar todo el contenido de la página. Por otro lado, existirá un usuario voluntario que trata de aquellos usuarios que quieran formar parte de este proyecto y quieran proporcionar información interesante relacionada con la igualdad de género. Por supuesto esa información tendrá que pasar por la supervisión del usuario administrador; el cual decidirá añadir o no el contenido. Y finalmente, se encuentra el usuario no registrado que será aquel que entre al sitio web y que consuma nuestro contenido sin tener que registrarse. 

La pagina web estará divida en dos partes: la información estática (contacto, quiénes somos, log-in)  y la información dinámica (noticias, articulos, reportajes, entrevistas, historias reales, consejos).

### 2. Escenarios
En este apartado crearemos ciertos escenarios supuestos donde imaginaremos el uso que le pueden dar nuestros usuarios a nuestro sitio web. A continuación se encuentran los siguientes escenarios:

#### 2.1. Escenario 1: Paula y su desconocimiento
Paula tiene 43 años, es directora informática de BOSCH Bilbao pero no todo es perfecto. Se encuentra dentro de una relación sentimental un tanto tóxica o eso empieza a sentir ella. No se atreve a hablar con su entorno sobre las situaciones que está viviendo con su actual pareja. Y como no tiene donde refugiarse decide sumergirse en Internet. En una de sus redes sociales (Facebook), allí encuentra una publicación que ha compartido una amiga suya y que trata sobre un sitio web donde tratan contenido relacionado con la igualdad de género; pero sobre todo es un lugar de refugio, ayuda y consejo. En consecuencia, Paula decide hacer clic en el enlace y entrar en hoyportimañanapormi.com. 

Paula encuentra un sitio web que muestra la realidad de la sociedad ante la igualdad de género, encuentra entrevistas con expertos (psicólogos, abogados) que tratan temas de violencia de género y sobre todo encuentra historias reales de otras mujeres que le hacen recapacitar que ella misma está viviendo una relación insana y que no puede permitirlo. Debido al impacto que tuvo para Paula este sitio web, decide ponerse en contacto con *hoyportimañanapormi.com* para pedir más información y para trasladarles su historia para que la publicasen con el objetivo de ayudar a otras personas como lo hicieron las historias de otras mujeres a ella. Por lo tanto, Paula es un usuario voluntario ya que se ha registrado en el sistema, cuenta con su propia cuenta y puede compartir contenido en la página web.

#### 2.2. Escenario 2: Juan y su trabajo para la universidad

#### 2.3. Escenario 3: Dolores y sus ganas de aprender

### 3. No objetivos
Esta versión *no* incluirá las siguientes funciones:

* Compra de productos
* Suscripción de pago
* Publicación diraria de contenido
* Un lugar físico de contacto (oficina)
* Opción de consumir contenido únicamente estando registrado

### 4. Detalles
#### 4.1. Requisitos funcionales de usuarios
Como se ha comentado en el anterior apartado, la página web dispondrá inicialmente de 3 perfiles de usuario distinto (usuario administrador, usuario voluntario y usuario no registrado), cada uno con requisitos funcinales específicos.

Así mismo, existirán 3 niveles jerarquicos: el primer nivel está formado por el usuario no registrado, el segundo nivel por el usuario voluntario y finalmente el tercer nivel por el usuario administrador del sitio web. Los usuarios de cada nivel tendrán asignadas sus funcionalidades pero también heredarán las de los niveles inferiores (el usuario administrador podrá acceder a las funcionalidades del voluntario y del no registrado; y el usuario voluntario podrá acceder a las del usuario no registrado). En la siguiente imagen se muestra la relación entre niveles. 

![Niveles de usuarios](/2-alcance/Niveles de usuarios.png)

A continuación se presentan los requisitos de funcionamiento especificos de cada perfil de usuario.

##### 4.1.1. Usuario no registrado.
El usuario no registrado lo describiriamos como el visitante ocasional y dispondrá de los siguientes requisitos funcionales: 

* **Acceso al contenido público:** este usuario tendrá acceso a todo el contenido que esté oficialmente publicado en el sitio web. No tendrá que registrarse para poder consumir nuestro contenido. Tendrá acceso a: noticias, reportajes, articulos, entrevistas, historias reales, consejos, quiénes somos y contacto.

* **Registrarse:** tendrán la opción disponible para registrarse en *hoyportimañanapormi.com* opción para convertirse en un usuario voluntario. 


##### 4.1.2. Usuario voluntario (registrado)
El usuario registrado heredará las funcionalidades del usuario no registrado y dispondrá de nuevos requisitos funcionales:

* **Registrarse:** deberan rellenar un formulario con los datos necesario y aceptar los términos legales sobre difusión y gestión de datos. 

* **Autentificarse:** para poder acceder al contenido los usuarios voluntarios deberan hacer un log-in (usuario y contraseña).

* **Realizar comentarios de mejoras y cambios:** la página web tendrá una funcionalidad para que los usuarios puedan realizar comentarios (privados) de mejoras o cambios en el contenido público. 

* **Compartir información:** los usuarios voluntarios podrán compartir contenido relacionado con la igualdad de género. Para ello, tendrán una lugar específico donde poder adjuntar la información. 


##### 4.1.3. Usuario administrador
El usuario administrador heredará las funcionalidades disponibles para los iveles inferiroes de usuario de la página web, y además dispondrá de los siguinetes requisitos funcionales:

- **Gestor de contenido**:
* **Agregar contenido**
* **Editar contenido**
* **Eliminar contenido**

-**Gestor de los perfiles registrados**:
* **Gestión de perfiles:** el administrador, en el caso que sea necesario, podrá cambiar las funcionalidades concretas del usuario voluntario o incluso añadir nuevas.
Gestión de la base de datos: el administrado del sitio web tiene acceso a la base de datos de los perfiles registrados. 

* **Gestión del contenido adjuntado por el usuario voluntario:** el administrador será quien analice el contenido compartido por los usuarios voluntarios y también será quien decida qué contenido se publicará y cuál no. 

* **Gestión de incidencias:** teniendo en cuenta que el administrador tiene acceso a la base de datos de los perfiles resgistrados, este gestionará posibles incidencias que ocurran durante el funcionamiento del sitio web (dar de baja usuarios, eliminar contenido, etc.).

-**Gestión de la configuración del sitio web**:
El **resto de tareas** relacionadas con el sitio web serán responsabilidad del usuario administrador: configuración de contenido, diseño, etc. 



## REQUERIMIENTOS DE CONTENIDOS

### Slow Content 



## REFERENCIAS
