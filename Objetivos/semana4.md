# Objetivos de la asignatura

### Cuarta semana [24 Octubre]

* [x] 1.Entender las arquitecturas de software en la nube de uso en la actualidad.

  Para la realización de este objetivo he consultado los **[apuntes de la asignatura](http://jj.github.io/CC/documentos/temas/Arquitecturas_para_la_nube)**. Resumuendo, podemos encontrarnos este tipo de arquitecturas:

  - **Arquitectura en capas:** es el desarrollo natural de la arquitectura cliente-servidor, creando 3 o más capas entre las que se suele incluir la capa de presentación, la de aplicación, la de lógica de negocio y la de acceso a datos.

  - **Arquitectura dirigida por eventos:** El elemento fundamental de esta arquitectura es la cola de eventos, que se originan en el usuario, pero también de una parte a otra de la arquitectura. A través de una cola de eventos, diferentes procesadores de eventos van extrayendo eventos de la cola y procesándolos de forma asíncrona.

  - **Arquitectura microkernel:** Se trata de una arquitectura más o menos monolítica, con un núcleo central al que se pueden añadir funcionalidades mediante plugins. El problema principal es la escalabilidad, ya que el núcleo puede representar un cuello de botella.

  - **Arquitectura basada en microservicios:** Una de las arquitecturas más populares hoy en día.Lo principal en una arquitectura de microservicios es que se trata de unidades que se van a desplegar de forma independiente, diferentes servicios que trabajarán de forma totalmente independiente unos de otros.

  - **Arquitectura basada en espacios:** En esta arquitectura, un espacio es compartido por una serie de unidades de procesamiento, que se comunican entre sí principalmente a través de ese espacio.

  ---

* [x] 2.Comprender el papel fundamental de la infraestructura virtual en este proceso.

   A mi parecer, el uso de infraestructuras virtuales simplifica mucho el proceso de desarrollo del software, ya que no te tienes que preocupar por el hardware requerido, conexiones de banda ancha... sino que el cliente obtiene acceso a los componentes virtualizados para construir con ellos su propia plataforma informática.

   He considerado interesante el siguiente bloque de información:

   IaaS proporciona acceso a recursos informáticos situados en un entorno virtualizado, la"nube" (cloud), a través de una conexión pública, que suele ser internet. En el caso de IaaS, los recursos informáticos ofrecidos consisten, en particular, en hardware virtualizado, o, en otras palabras, infraestructura de procesamiento. La definición de IaaS abarca aspectos como el espacio en servidores virtuales, conexiones de red, ancho de banda, direcciones IP y balanceadores de carga. Físicamente, el repertorio de recursos de hardware disponibles procede de multitud de servidores y redes, generalmente distribuidos entre numerosos centros de datos, de cuyo mantenimiento se encarga el proveedor del servicio cloud. El cliente, por su parte, obtiene acceso a los componentes virtualizados para construir con ellos su propia plataforma informática.

   Para más información, visitar el **[enlace del articulo relacionado](https://www.interoute.es/what-iaas)**

---

* [x] 3.Entender en qué consiste los servicios web y cómo desplegarlos en la nube

   Un servicio web es una vía de intercomunicación e interoperabilidad entre máquinas conectadas en Red. En el mundo de Internet se han popularizado enormemente, ya se trate de web services públicos o privados. Generalmente, la interacción se basa en el envío de solicitudes y respuestas entre un cliente y un servidor, que incluyen datos. El cliente solicita información, enviando a veces datos al servidor para que pueda procesar su solicitud. El servidor genera una respuesta que envía de vuelta al cliente, adjuntando otra serie de datos que forman parte de esa respuesta. Por tanto, podemos entender un servicio web como un tráfico de mensajes entre dos máquinas.

   Ver este **[enlace](https://www.arsys.es/blog/programacion/diseno-web/web-services-desarrollo/)** para ir al artículo relacionado.

   Además de los tipos de despliegue, existen diferentes soluciones de adopción Cloud para adaptarse a las diversas necesidades de las empresas y sus usuarios. Cada modelo de servicio se estructura en una capa diferente y proporciona distintos niveles de control, gestión y flexibilidad.

   Según el nivel en el que operan, existen tres modelos principales de servicios Cloud:

   - Saas (Software as a Service)

   - PaaS (Platform as a Service)

   - Iaas (Infrastructure as a Service)

 Para obtener más información, consultar el **[enlace relacionado](https://profile.es/blog/servicios-cloud-que-es-iaas-saas-y-paas/)**

 ---

* [x] 4.Revisar los resultados del primer hito y entender los fallos.

 He revisado los resultados del **[hito](https://github.com/JJ/CC-18-19/blob/master/proyectos/hito-1.md)**, y he obtenido la máxima calificación. (Nombre: Martín Valera Jonathan)

 ---

* [x] 5.Tener manejo básico de los lenguajes usados en herramientas de provisionamiento, Python y Ruby.

 Tanto en python como en ruby, tengo un manejo básico, ya que los he utilizados ambos lenguajes para realizar algunas tareas concretas a lo largo del grado de ingeniería informática.

 En caso de ser necesario su utilización, puedo consultar los siguientes manuales para consultar sintaxis...

 - **[Guía de usuario para Ruby](http://es.tldp.org/Manuales-LuCAS/doc-guia-usuario-ruby/guia-usuario-ruby.pdf)**
 - **[Guía de usuario para python](http://docs.python.org.ar/tutorial/pdfs/TutorialPython3.pdf)**

 ---

* [x] 6.Darse de alta en servicios PaaS como zeit.co y Heroku.

 Ya me he registrado en zeit.co y heroku.

 En **[zeit.co](https://zeit.co/)** me ha dejado identificarme mediante mi cuenta de github. Una vez dentro, se presenta la siguiente vista:

 ![img](https://raw.githubusercontent.com/jmv74211/CC-Ejercicios/master/Objetivos/images/zeit.co.jpg)

 Respecto a **[Heroku](https://www.heroku.com/platform)**, me he tenido que registrar introduciendo mis datos. Una vez dentro, se presenta la siguiente vista:

  ![img](https://raw.githubusercontent.com/jmv74211/CC-Ejercicios/master/Objetivos/images/heroku.jpg)

 ---

* [x] 7.Entender por qué no se hace `git pull` sino `git pull --rebase` y
  como arreglarlo en ese caso
  usando un squash commits con
  [`git rebase -i`](https://stackoverflow.com/questions/5189560/squash-my-last-x-commits-together-using-git).

 `git pull` ejecuta `git fetch` con los parámetros dados y llama a `git merge` para fusionar los encabezados de las ramas recuperadas en la rama actual. Con `--rebase`, ejecuta `git rebase` en lugar de `git merge`.

 En el caso más simple de no colisiones:

 - **con rebase:** rebases tus commits locales ontop de HEAD remoto y no crea un commit de merge / merge.
 - **sin / normal:** se fusiona y crea un compromiso de fusión.

 Hay un ejemplo visual que aclara bastante y me ha ayudado a entender la diferencia. El ejemplo está disponible en este **[artículo](https://code.i-harness.com/es/q/120db5f)**.

 Un squash commit significa, desde un punto de vista idiomático, mover los cambios introducidos en dicho commit a su padre para unificarlos. Más información **[aquí](https://stackoverflow.com/questions/35703556/what-is-squashing-commits-in-git)**.

 Para hacer squash de un commit, hay que utilizar `git rebase -i <after-this-commit>`

 ---

* [x] 8.Proponer temas para el siguiente seminario/recuperación.

 Un posible tema de mi interés es un seminario sobre cómo escribir los test que debe de pasar el código y cómo usar **[Travis](https://travis-ci.org/)** para integrar el código.
