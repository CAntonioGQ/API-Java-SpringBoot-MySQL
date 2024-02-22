# CRUD Rápido con Spring Boot y Hibernate

Este proyecto implementa un simple CRUD (Crear, Leer, Actualizar, Eliminar) utilizando Spring Boot y Hibernate para gestionar información de estudiantes.

## Requisitos Previos

- [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/javase-downloads.html) - Se recomienda Java 11 o superior.
- [Maven](https://maven.apache.org/download.cgi) - Gestor de dependencias.
- [MySQL](https://www.mysql.com/) - Base de datos relacional.
- [Postman](https://www.postman.com/) - Para probar los endpoints.

## Configuración de la Base de Datos

1. Crea una base de datos MySQL llamada `crudrapido`.
2. Actualiza las credenciales de la base de datos en el archivo `application.properties`.

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/crudrapido
spring.datasource.username=tu_usuario
spring.datasource.password=tu_contraseña
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
spring.jpa.show-sql=true
spring.jpa.hibernate.ddl-auto=update


LEA el .txt de base de datos, ya que unicamente necesita crear la base de datos crudrapido.

Ejecución de la Aplicación
Clone el repositorio:

git clone https://github.com/CAntonioGQ/API-Java-SpringBoot-MySQL
cd crud-rapido-spring-boot

Compile y ejecute la aplicación con Maven:
mvn spring-boot:run

La aplicación estará disponible en http://localhost:8080/


Tecnologías Utilizadas
Spring Boot
Hibernate
MySQL
Maven
```
## Contribuciones
¡Las contribuciones son bienvenidas! Si tienes sugerencias o mejoras para este proyecto, siéntete libre de abrir un problema o enviar un pull request.

