# Ejercicios del tema 1

---

##### Ejercicio 1 - Buscar una aplicación de ejemplo, preferiblemente propia, y deducir qué patrón es el que usa. ¿Qué habría que hacer para evolucionar a un patrón tipo microservicios?

Para la realización de este ejercicio, voy a utilizar como aplicación la realizada
en mi proyecto final de grado. Dicha aplicación consiste en una plataforma para
la gestión de actividades deportivas para los alumnos de la UGR.

Se puede acceder a ésta a través del siguiente **[enlace](http://pad-ugr.hostingerapp.com/index.php)**.

Esta aplicación tiene una arquitectura monolítica, implementada mediante clases y
con un controlador que recibe y gestiona las peticiones a través del patrón MVC.

Para poder evolucionar esta arquitectura a una de microservicios, debería de descomponer
y delegar diferentes tareas en pequeños microservicios independientes que pudieran transmitirse la información mediante una API REST y que el conjunto de peticiones se gestionara mediante una cola de eventos.

Por ejemplo, podría tener los siguientes microservicios:

- Microservicio para el registro de usuarios.
- Microservicio para la identificación de usuarios.
- Microservicio para gestionar la capa de acceso a los datos de la BD.
- Microservicio para la gestión de mensajes privados entre usuarios.
- Microservicio para la gestión de actividades deportivas.
- Microservicio para la gestión de clubs.
- Microservicio para la gestión de la información del usuario.
- Microservicio para la gestión de notificaciones.
- Microservicio para la capa de presentación.

##### Ejercicio 2 -En la aplicación que se ha usado como ejemplo en el ejercicio anterior, ¿podría usar diferentes lenguajes? ¿Qué almacenes de datos serían los más convenientes?

Sí, cada microservicio podría realizarlo en un lenguaje diferente al resto. Gracias a la API REST podemos comunicar todos los microservicios independientemente del lenguaje en el que estén implementados.

Como posible almacén de datos podría usar una base de datos relacional o no relacional. En mi caso utilicé una base de datos relacional con MySQL.

Considero que en este caso sería mejor haber utilizado una base de datos NoSQL, ya que al realizar una estructura descentralizada mediante microservicios, podemos hacer una distribución de los datos descentralizada, de forma que sea más escalable.

En este **[enlace](https://blog.pandorafms.org/es/nosql-vs-sql-diferencias-y-cuando-elegir-cada-una/)** se proporciona una breve enlace comparación entre bases de datos relacionales y NoSQL.
