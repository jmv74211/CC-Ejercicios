# Objetivos de la asignatura

### Segunda semana [10 Octubre]


* [x] 1.Comprender la metodología de desarrollo, prueba y despliegue en la que se basa la computación en nube.

  He leído el siguiente **[artículo](http://www.mtp.es/como-implantar-una-metodologia-de-entrega-continua-y-devops/)** y he aclarado conceptos además de concienciarme de la importancia que tiene esta metodología en el marco de desarrollo actual. Aquí os muestro un breve resumen del contenido:

  Mantener el sistema tradicional de construcción y despliegue de software ya no tiene sentido. Se hace cada vez más necesario adoptar otro basado en la filosofía Lean, que permita la optimización de los procesos, la reducción de costes mediante la eliminación de las tareas manuales, la reducción del time-to-market y la reducción del riesgo a la hora de realizar modificaciones en el entorno.

  Además, muchos procesos se siguen llevando a cabo de forma manual, lo que da lugar a la generación de errores que acaban provocando trabajo extra, retrasos, necesidad de asignar más recursos y, por tanto, el encarecimiento del proyecto. Esta situación puede solucionarse mediante la adopción de prácticas de Entrega Continua y **[DevOps](https://www.paradigmadigital.com/techbiz/que-es-devops-y-sobre-todo-que-no-es-devops/)**.

  En este necesario cambio de cultura, la automatización juega un papel fundamental a la hora de asegurar la calidad en los procesos de despliegue del software. Si el proceso de construcción, pruebas y despliegue no está automatizado, no es reproducible. Es decir, al trabajar de forma manual, cada vez que se lleve a cabo un despliegue de una nueva versión se hará de forma distinta, porque resultará imposible auditar e identificar los errores cometidos a la hora de realizar cambios en la aplicación, en la configuración del sistema o en los entornos. No hay control en el proceso de release y, por lo tanto, no hay forma de asegurar la calidad final del producto.

  Para más información: **[enlace al artículo relacionado](http://www.mtp.es/como-implantar-una-metodologia-de-entrega-continua-y-devops/)**

---

* [x] 2.Entender las características de las aplicaciones que se despliegan en la nube.

  La computación en la Nube es comúnmente llamada Cloud Computing . Esta presenta distintas características clave que la diferencian de la computación tradicional:

  - **Escalabilidad y elasticidad:** Las plataformas en la nube tus sistemas se adaptarán a la carga a la que están siendo sometidos, por lo que no se agotará el almacenamiento o la capacidad de computación de tu aplicación.

  - **Independencia entre el dispositivo y la ubicación:** La computación en la nube se caracteriza por la puesta a disposición de consolas de administración y múltiples ambientes de trabajo que pueden ser accedidas a través de un dispositivo móvil, tu editor de código favorito o en tu computador, independientemente del lugar en el que te encuentres ubicado.

  - **Seguridad:**  El usuario de la nube es responsable de la seguridad a nivel de aplicación. El proveedor de la nube es responsable de la seguridad física.

  - **Costo:** Los costos se reducen notablemente. Un servidor en la nube convierte los gastos de capital en gastos de funcionamiento

  - **Rendimiento:** Todos los recursos están dispuestos para la optimización del resultado final. Se crean múltiples integraciones para que el usuario esté en capacidad de hacer un seguimiento permanente e implementar correcciones que permitan obtener aún más capacidad de los mismos recursos.

  - **Mantenimiento:** Este proceso se reduce a la asignación de personal capacitado para manejar servicios de seguimiento. La plataforma se encargará de lo demás, ya que el mantenimiento a los sistemas se puede configurar para que se dé automáticamente. Esto reduce tiempos de implementación que resulta en que se pueda centrar la atención en la producción del software.

    Para más información visitar el **[enlace](https://www.nextu.com/blog/6-caracteristicas-de-la-computacion-en-la-nube/)** del artículo relacionado.

    ---

* [x] 3.Manejar con soltura los diferentes recursos de línea de órdenes, especialmente en Linux.

  * [x] 3.1 Saber manejar la historia de comandos anteriores.

    Como ya se comentó en los **[objetivos de la semana1](https://github.com/jmv74211/CC-Ejercicios/blob/master/Objetivos/semana1.md)**, se ha practicado distintas órdenes de Linux en la shell. Las referencias básicas que se utilizaron son:
    - Principales comandos básicos de Linux: Enlace **[aquí](https://hipertextual.com/archivo/2014/04/comandos-basicos-terminal/)**.

    * Hay un pdf disponible que realiza una gran explicación de la órdenes de comandos en Linux. Está disponible** [aquí](https://drive.google.com/file/d/0Bz_k22Jugr3UOUs5U1VzQzBRVEE/view)**.

  * [x] 3.2 Configurar la línea de órdenes para presentar información de repos.

    He instalado el terminal **[ZSH](https://es.wikipedia.org/wiki/Zsh)** y descargado el pack **[oh MY ZSH](https://vmcreativo.com/como-instalar-oh-my-zsh-en-tu-consola-y-algunos-plugins-utiles/)** para personalizar el tema del terminal.

    - Enlace a **[vídeo](https://www.youtube.com/watch?v=WVDqCzrs9yU)** donde explica cómo instalarlos
    - Enlace al **[repositorio](https://gist.github.com/derhuerst/12a1558a4b408b3b2b6e)** de descarga


  * [x] 3.3 Conocer permisos y cuales usar en cada momento.

    Tipos de permisos en Linux

    - **Clases:** Estas determinan que usuarios pueden acceder al archivo o carpeta.
    - **Permisos:** Estos determinan la tarea que pueden ejecutar los usuarios autorizados en dichos archivos

    Dentro de este esquema identificamos tres (3) tipos de clases:

    - **Propietario:** Es la persona que ha creado el archivo o la carpeta.

    - **Grupo:** Dentro de este parámetro definiremos el grupo de usuarios que tendrán acceso al archivo o carpeta.

    - **Otros:** Dentro de este parámetro están incluidos los usuarios particulares.

    Ahora contamos con tres tipos de permisos de edición de nuestros archivos o carpetas, éstos son:

    - **Lectura:** Esta opción permite que el usuario vea el archivo pero no le da la potestad de realizar cambios en el mismo lo cual nos da un alto nivel de seguridad ya que no podrán editarlo, copiarlo o borrarlo.

    - **Escritura:** Al otorgar este permiso permitimos que los usuarios que acceden al archivo o carpeta puedan realizar sobre el mismo cualquier tipo de edición, Copiar, cortar, borrar) lo cual pone en riesgo la integridad del mismo.

    - **Ejecutar:** Al activar esta opción, la cual viene por defecto deshabilitada, podemos ejecutar archivos.

    Para saber más acerca de este tema, hay un **[artículo](https://www.solvetic.com/tutoriales/article/1458-entender-los-permisos-linux-chmod/)** que es el que he leído, donde viene todo muy bien explicado

---

* [x] 4.Haber entregado el hito 0 del proyecto y entender qué se buscaba con el mismo.

  El hito se ha entregado correctamente. Disponible en este **[enlace](https://github.com/JJ/CC-18-19/blob/master/proyectos/hito-0.md)**, con nombre Martín Valera Jonathan.

---

* [x] 5.Comprender el primer hito del proyecto..

  El hito se ha entregado correctamente. Disponible en este **[enlace](https://github.com/JJ/CC-18-19/blob/master/proyectos/hito-1.md)**, con nombre Martín Valera Jonathan.
