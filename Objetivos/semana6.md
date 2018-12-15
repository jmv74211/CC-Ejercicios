# Objetivos de la asignatura

### Sexta semana [7 Noviembre]

* [ ] 1.Aprender a usar diferentes sistemas de provisionamiento de máquinas virtuales en la nube.

  Una gran cantidad de herramientas están apareciendo en el mercado para ayudar a los administradores de sistemas y a los DevOps a simplicar su trabajo y a automatizar procesos en cantidades ingentes de servidores.

  Presentamos tres ejemplos de herramientas de este tipo:

- **Puppet**, con una gran madurez, open source, basado en ruby, con agentes en los servidores a gestionar. Se basa en un lenguaje de dominio propio que permite generar estados finales en los servidores por medio de “manifests”. Orientado a administradores de sistemas, da soporte de monitorización de los cambios. Cada media hora, el servidor se pone en contacto con los clientes y evalúa los cambios. Esto es posible gracias al “catalog”. Permite comprobar el estado final deseado de los servidores y, si no es correcto, cambia el estado para que sea el que queramos. Tiene soporte para Windows y Linux, pero si queremos AIX o Solaris, toca usar la versión Enterprise.

- **Chef**, con objetivos similares a Puppet, permite generar recipes basados en lenguaje ruby. Orientado más a desarrolladores, con experiencia en ruby, posee una curva de aprendizaje menor que la de Puppet, pero con un mayor control sobre el estado final del servidor. Posee una aproximación procedural, lo que facilita el control de los procesos hasta llegar al final del estado deseado.

- **Ansible**, con una clara diferencia con los demás, no necesita de un servidor maestro ni tampoco de agentes que se instalen en los nodos a gestionar. Se basa en una estación con el mapa de los servidores a gestionar y las credenciales SSH para su conexión. Basado en Python, usa playbooks para saber el estado final deseado de los servidores. El playbook es ejecutado en orden, lo que lo hace más simple de entender. Los playbooks están escritos en Yaml (Similar al XML), lo que permite una interpretación sencilla de las instrucciones alojadas en él.

  Respecto al uso de dichas herramientas, por ahora vamos a usar Ansible para el hito 3, y vamos a recibir un seminario de Chef, dado que ha sufrido cambios. Tras dicho seminario se realizarán pruebas y se cumplirá este objetivo.

  ---

* [x] 2. Entender los diferentes conceptos subyacentes: servicio, estado.

  Un **servicio web** es una vía de intercomunicación e interoperabilidad entre máquinas conectadas en Red. Generalmente, la interacción se basa en el envío de solicitudes y respuestas entre un cliente y un servidor, que incluyen datos.

  Cada recurso posee un **estado** interno, que no puede ser accedido directamente desde el exterior. Lo que sí es accesible desde el exterior es una o varias representaciones de dicho estado. Por representación se entiende un formato de datos concreto usado para la transferencia de una copia del estado público del recurso entre el cliente y el servidor. La implementación del recurso decide que información es visible o no desde el exterior, y que representaciones de dicho estado se soportan.

   En REST todos los recursos comparten una interfaz única y constante. Todos los recursos tienen las mismas operaciones. Las operaciones nos permiten manipular el estado público del recurso. En un sistema REST típico se definen cuatro operaciones (CRUD).

   Según esta información, y la que he leído en varias páginas web, no me ha quedado claro el concepto de estado, así que trataré de entender este concepto con la ayuda del profesor.

   Referencias de a información:
  - [https://blog.bi-geek.com/servicios-web-restful/](https://blog.bi-geek.com/servicios-web-restful/)
  - [https://eamodeorubio.wordpress.com/2010/07/26/servicios-web-2-%C2%BFque-es-rest/](https://eamodeorubio.wordpress.com/2010/07/26/servicios-web-2-%C2%BFque-es-rest/)

  ---

* [x] 3. Entender el concepto de servicio web.

  Un web service es una vía de intercomunicación e interoperabilidad entre máquinas conectadas en Red. En el mundo de Internet se han popularizado enormemente, ya se trate de web services públicos o privados. Generalmente, la interacción se basa en el envío de solicitudes y respuestas entre un cliente y un servidor, que incluyen datos.

  En este caso, la aplicación que se va a desplegar en la asignatura de cloud computing es básicamente un servicio web que recibe una serie de peticiones (PUT,POST,GET Y DELETE) y devuelven una serie de información utilizando REST.

  Referencias a la información del primer párrafo:
  - https://www.arsys.es/blog/programacion/diseno-web/web-services-desarrollo/

  ---

* [x] 4.Conocer diferentes lugares donde haya imágenes de sistemas operativos listas para usar.

 En la web existen una gran diversidad de empresas que ponen a disposición de sus clientes imágenes de sistemas operativos ya configurados en temas de seguridad, servicios...

 Un ejemplo es la empresa sevillana [Bitnami](https://bitnami.com/) que se encarga de proveer imágenes ya preconfiguradas con diferentes servicios.

 ---

* [ ] 5. Instalar y configurar diferentes sistemas de provisionamiento.

  Por ahora solo se ha utilizado el sistema de aprovisionamiento de ansible. Puede que quizás más adelante, se utilice un sistema de aprovisionamiento alternativo como es [Cheff](https://docs.chef.io/provisioning.html)

  ---
