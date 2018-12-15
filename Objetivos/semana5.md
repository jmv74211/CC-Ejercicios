# Objetivos de la asignatura

### Quinta semana [31 Octubre]

* [x] 1.Comprender el tipo de aplicaciones que se despliegan en la nube.

  He estado leyendo varios artículos para intentar comprender el objetivo de esta pregunta, y la conclusión final (no sé si con ello respondo a la cuestión planteada) es la siguiente:

  Casi todos los recursos de TI pueden estar en la nube: un programa o aplicación, un servicio o una infraestructura completa. Por ejemplo, si un negocio quisiera construir una infraestructura de TI, lo habitual sería instalar los servidores, el software y los recursos de red que necesita. pero casi todos esos servicio y recursos ahora son accesibles a través de terceros que los ofrecen en la nube.

  Por lo tanto, entiendo que podemos adaptar cualquier aplicación a la nube, adaptando nuestras necesidades al conjunto de servicios ofertados.

  Click **[aquí](https://www.powerdata.es/cloud)** para acceder a la página de donde se ha obtenido la información. Decir que este artículo me ha parecido interesante y puede aclarar muchos conceptos sobre cloud.

  ---

* [x] 2. Entender el concepto de infraestructura virtual y cómo describir
   infraestructura mediante software, que se verá en [este seminario](https://www.meetup.com/es-ES/Granada-Geek/events/255973562/), como avance al tema siguiente.

   Para profundizar un poco más en este tema, he consultado los apuntes de JJMerelo de Introducción a la infraestructura virtual: concepto y soporte físico, disponibles en el siguiente **[enlace](http://jj.github.io/IV/documentos/temas/Intro_concepto_y_soporte_fisico)**.

   En dicha documentación se dice lo siguiente:

   Una **infraestructura virtual** será un recurso-procesador, memoria, disco, conjunto de aplicaciones o incluso una sola aplicación o función- que no está asociado directamente a su equivalente real (no tiene un procesador físico, o un disco físico exclusivo) sino que se ha creado a través de una serie de mecanismos computacionales para funcionar como tal.

   Respecto a la descripción de infraestructura mediante software, he consultado la siguiente información **[articulo](https://www.hpe.com/es/es/what-is/software-defined-infrastructure.html)**, que dice lo siguiente:

   La infraestructura definida por software consta de recursos de computación, red y almacenamiento totalmente virtualizados que están agrupados de manera lógica y pueden gestionarse como si fueran software. Esto permite el aprovisionamiento de infraestructura basado en políticas y permite la automatización de TI.

   Ansible y otras herramientas, como Chef y Puppet, permiten describir la infraestructura en la que va a ejecutarse una aplicación usando código; simplemente con tener acceso de administración a una máquina virtual.

   ---

* [x] 3. Conocer las diferentes ofertas de PaaS en la nube

  En primer lugar he utilizado el PaaS [Heroku](https://dashboard.heroku.com/) para realizar el hito número 2 de la asignatura de cloud computing. También me he registrado en [Zeit](https://zeit.co/) y he estado viendo por encima como funciona.

  Después he consultado varias webs en las que se muestra información acerca de los PaaS más utilizados, y he encontrado este [artículo](https://cioperu.pe/fotoreportaje/9469/las-10-empresas-mas-poderosas-de-paas/?foto=2) que muestra las 10 empresas más poderosas de PaaS.

  ---

* [x] 4.Instalar las herramientas de línea de órdenes de las herramientas cloud.

  Para realizar el hito 4 de la asignatura de cloud computing, he instalado la herramienta de órdenes de azure: **[Azure CLI](https://docs.microsoft.com/es-es/cli/azure/install-azure-cli?view=azure-cli-latest)**. Dicha herramienta la he utilizado para realizar el script **[acopio.sh](https://github.com/jmv74211/Proyecto-cloud-computing/acopio.sh)** que crea una máquina virtual en Azure y la aprovisiona utilizado ansible.

  ---

* [x] 5.  Hacerse con alguna cuenta gratuita o bonificada de cloud.

  Para poder realizar los hitos de la asignatura, el profesor nos ha proporcionado una cuenta con bonificaciones de estudiante para la plataforma de [Azure](https://azure.microsoft.com/es-es/) y [GoogleCloudPlatform](https://cloud.google.com/).

  ---

* [x] 6. Aprender la mínimo de los lenguajes necesarios para trabajar en la nube: Perl, Python y Ruby.

  En este caso se ha utilizado mayoritariamente Python para elaborar los microservicios que se han desplegado en la nube. También se ha investigado nociones básicas acerca de Ruby y he leído por encima la [documentación de Perl](http://perldoc.perl.org/perl.html#Tutorials) (En el máster es imposible encontrar tiempo para intentar aprender un lenguaje nuevo(en el tiempo libre, que no es que haya mucho))

  ---
