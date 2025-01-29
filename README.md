  # Spring Boot 3 JSP JPA MySQL Security

Last updated: 29-01-2025

- Java 17
- Spring Boot 3.3

# Config at Azure App Service

- Java 17
- Tomecat 10.1
- Copy the ROOT.war to wwwroot - webapps ( Stop / Start the Web App by Azure Portal )

# Usage

- Download or fork the source code from GitHub

# Create the file application.properties and place it in the resources folder

spring.jpa.hibernate.ddl-auto=update

spring.datasource.url=jdbc:mysql:// the name of your mysql host / the name of your database

spring.datasource.username=your username 
spring.datasource.password=your password

spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
spring.jpa.show-sql: true

spring.mvc.view.prefix=/WEB-INF/jsp/
spring.mvc.view.suffix=.jsp

# Run the Web Application locally by open a terminal in the folder of the Spring Boot Web App

- ./mvnw spring-boot:run 

# Show the JSP welcome:

http://localhost:8080

# Login:

http://localhost:8080/login
