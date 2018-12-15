# Objetivos de la asignatura

### Séptima semana [14 Noviembre]

* [x] 1.Entender las arquitecturas de software en la nube de uso en la actualidad.

  Para entender las arquitecturas software para la nube se ha utilizado los [apuntes proporcionados](http://jj.github.io/CC/documentos/temas/Arquitecturas_para_la_nube) por @jjMerelo.

  Más allá de las antiguas arquitecturas monolíticas que se usaban, ahora predomina el uso de arquitecturas basadas en microservicios, que es la que hemos estado usando para el desarrollo de nuestra aplicación web que vamos a desplegar en la nube.

  Conviene bien saber la diferencia que hay entre las distintas arquitecturas y he comprendido la versatilidad y la fácil escalabilidad que presentan las arquitecturas basadas en microservicios.

  ---

* [x] 2.Comprender el papel fundamental de la infraestructura virtual en este proceso.

  Hoy día, el explosivo crecimiento de los datos
  digitales ha impuesto nuevas exigencias no
  solo en términos informáticos, sino también
  en redes empresariales y arquitecturas de
  almacenamiento tradicionales, creando
  cuellos de botella que impiden ofrecer un
  rendimiento y unos servicios ágiles. Para
  mitigar estos desafíos, las empresas deben
  avanzar siguiendo la curva de madurez de
  la nube y ampliando la virtualización más
  allá de la informática hasta los dominios del
  almacenamiento y de la red con el objetivo de
  alcanzar mayores niveles de automatización
  y coordinación en el aprovisionamiento de
  autoservicio y acuerdos a nivel de servicio
  (SLA) en tiempo real.

  Este primer párrafo nos resumen el principal auge e importancia de la infraestructura virtual definida por software que nos permite poder desplegar nuestra aplicación de forma rápida y sencilla en diferentes infraestructuras como cloud.

  Referencias:
  - https://www.intel.la/content/dam/www/public/lar/xl/es/documents/white-papers/enterprise-cloud-infrastructure-paper-spa.pdf

  ---

* [x] 3.Entender en qué consiste la infraestructura como software.

  La infraestructura definida por software consta de recursos de computación, red y almacenamiento totalmente virtualizados que están agrupados de manera lógica y pueden gestionarse como si fueran software. Esto permite el aprovisionamiento de infraestructura basado en políticas y permite la automatización de TI.

  En nuestro caso, hemos definido infraestructura como software ya sea a través de el cliente de Azure o un script de ansible para aprovisionar las máquinas virtuales.

  Referencias:
  - https://www.hpe.com/es/es/what-is/software-defined-infrastructure.html

  ---

* [x] 4.Tener manejo básico de los lenguajes usados en herramientas de provisionamiento, Python y Ruby.

  Considero que tengo un manejo básico en python, ya que ha sido el lenguaje de programación que he utilizado para desarrollar los microservicios de esta asignatura. Sin embargo no he utilizado Ruby en esta asignatura, pero si la he utilizado puntualmente en otra asignatura, por lo que también tengo un manejo básico (en este caso inferior a python).

  ---

* [x] 5.Poner a punto hipervisores de uso local y cuentas cloud que permitan usar máquinas virtuales para provisionar.

  Para el desarrollo del hito 3 se ha utilizado vagrant y virtualbox para la creación de las máquinas virtuales locales, y he aprovisionado dichas máquinas virtuales locales y la creada en azure con ansible.

  ---
