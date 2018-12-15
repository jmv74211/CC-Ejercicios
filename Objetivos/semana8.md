# Objetivos de la asignatura

### Octava semana [21 Noviembre]

* [x] 1. Entender los mecanismos básicos de los hipervisores y su soporte hardware.

  El software denominado hipervisores separa los recursos físicos de los entornos virtuales, es decir, todo lo que necesitan los recursos. Los hipervisores pueden conformarse como elementos principales de un sistema operativo (como una computadora portátil) o se pueden instalar directamente en el hardware (como un servidor), que es la forma en que la mayoría de las empresas virtualizan. Los hipervisores toman los recursos físicos y los dividen de manera tal que los entornos virtuales puedan usarlos.

  Leyendo esta información entiendo que el hipervisor toma recursos físicos y los abstrae para que se puedan utilizar virtualmente.

  Los hipervisores pueden clasificarse en dos tipos:
  - **Tipo I:** También denominado nativo, unhosted o bare metal (sobre el metal desnudo), es software que se ejecuta directamente sobre el hardware, para ofrecer la funcionalidad descrita.

  - **Tipo II:** También denominado hosted, es software que se ejecuta sobre un sistema operativo para ofrecer la funcionalidad descrita.

  Referencias:
  - https://www.redhat.com/es/topics/virtualization/what-is-virtualization

  - https://es.wikipedia.org/wiki/Hipervisor

  ---

* [x] 2. Conocer herramientas de alto nivel que permitan trabajar con los hipervisores localmente o en la nube.

  Podemos encontrarnos las siguientes herramientas para trabajar localmente:
  - Linux: KVM.
  - Oracle: VirtualBox.
  - VirtualBox OSE (desde la v4.0 fusionado en VirtualBox).
  - VMware: Workstation (de pago).
  - Server (gratis).«Tipos de hipervisores».
  - Player (gratis).«Tipo de hipervisores».
  - QEMU (varios sistemas operativos soportados).
  - Microsoft: Virtual PC.

  Según este [artículo](https://www.nettix.com.pe/blog/cloud/los-hipervisores-software-libre-mas-usados-en-la-nube), los hipervisores más utilizados en la nube son:
   - Xen Cloud Platform (XCP)
   - KVM
   - VirtualBox
   - OpenVZ
   - LXC

  ---

* [x] 3. Entender los diferentes niveles de definición de infraestructura y cómo trabajan unos con otros.

  A nivel de tecnología se aprecian diferentes niveles de de virtualización, pero hasta no hace demasiado tiempo se solía hablar, desde el punto de vista comercial se habla de tres niveles: Infrastructure, Platform y Software as a service

  Para comprender más sobre este tema, he leído la información relacionada en los [apuntes](http://jj.github.io/IV/documentos/temas/Intro_concepto_y_soporte_fisico) de @jjMerelo

  ---
