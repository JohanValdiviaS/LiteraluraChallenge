Challenge Literatura

![Ejemplo de Imagen](./images/badge-literalura.png)

Este proyecto es parte del Challenge Literatura del programa de estudio Oracle Next Education (Backend) impartido por Alura Latam. El objetivo es desarrollar una aplicación para gestionar libros y autores utilizando Spring Boot y una base de datos PostgreSQL.

Requisitos
Java Development Kit (JDK) 17 o superior
Maven 3.6.0 o superior
PostgreSQL (debe estar instalado y configurado)
Configuración
Clonar el repositorio:

bash
Copiar código
git clone https://url-del-repositorio.git
cd challenge-literatura
Configurar la base de datos:

Asegúrate de tener PostgreSQL instalado y ejecutándose localmente.

Crea una base de datos llamada challenge_literatura.

Verifica y ajusta las configuraciones de conexión en src/main/resources/application.properties:

properties
Copiar código
spring.datasource.url=jdbc:postgresql://localhost:5432/challenge_literatura
spring.datasource.username=tu_usuario
spring.datasource.password=tu_contraseña
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.PostgreSQLDialect
spring.jpa.hibernate.ddl-auto=update
Compilar y ejecutar la aplicación:

Puedes compilar y ejecutar la aplicación usando Maven:

bash
Copiar código
mvn spring-boot:run
O puedes compilar el proyecto y luego ejecutarlo como un JAR:

bash
Copiar código
mvn clean package
java -jar target/challenge-literatura-1.0.2.jar
Acceder a la aplicación:

La aplicación estará disponible en http://localhost:8080.

Uso
La aplicación ofrece un menú interactivo en la consola para buscar libros por título, listar libros registrados, listar autores registrados, buscar autores vivos en un determinado año, y listar libros por idioma.
Tecnologías Utilizadas
Spring Boot
Spring Data JPA
PostgreSQL
Maven
