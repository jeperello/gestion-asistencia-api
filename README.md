# gestion-asistencia-api
Proyecto para gestionar asistencias en escuela rural.

El primer paso fue descargar el proyecto base de Spring Boot 
https://github.com/spring-guides/gs-securing-web.git
El mismo contiene las dependencias:
- Spring Boot Starter Web: se utiliza para crear aplicaciones RESTful utilizando Spring MVC. Tambien es muy util y agil de utilizar ya que contiene un server Tomcat integrado.
- Spring Boot Security Starter: conjunto de dependencias que me ayudara a dar la seguridad y el control necesario para todos los servicios del proyecto, tanto para los usuarios y sus roles.
- spring-security-test Y spring-boot-starter-test: para realizar los Test.
- springdoc-openapi-starter-webmvc-ui: dependencia para utilizar Sagger UI para documentar de forma sencilla y rapida la API.
- spring-boot-starter-thymeleaf: esta dependencia sirve para crear las vistas de un proyecto, para este caso solo utilizaremos las que trae por defecto el proyecto base para probar los permisos de los roles. Se puede quitar al finalizar el proyecto, ya que me centrare en la construccion de los servicios back-end, para la API solicitada.
- 
