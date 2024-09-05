# AarogyaNiketan

AarogyaNiketan is a demo project built with Spring Boot. It serves as a backend for a healthcare application, demonstrating various Spring Boot features including web, security, data access, and more.

## Tech Stack

- **Java 1.8**: The programming language used for the application.
- **Spring Boot 2.5.3**: The framework used to build the application.
  - **Spring Boot Starter Actuator**: Provides production-ready features such as monitoring and management.
  - **Spring Boot Starter Data JPA**: Used for interacting with relational databases with JPA.
  - **Spring Boot Starter Data REST**: Builds hypermedia-based RESTful APIs with Spring Data repositories.
  - **Spring Boot Starter Security**: Adds security features like authentication and authorization.
  - **Spring Boot Starter Validation**: Provides support for Java Bean validation.
  - **Spring Boot Starter Web**: Used to build web applications, including RESTful services.
  - **Spring Boot DevTools**: Provides features to improve the development experience.
- **JSON Web Token (JWT)**: Used for secure authentication.
- **MySQL and PostgreSQL**: Databases used for data persistence.
- **Lombok**: A Java library that reduces boilerplate code.
- **Spring Data Envers**: Provides auditing capabilities.
- **Swagger (Springfox)**: Used to document RESTful APIs.
- **Asciidoctor**: For generating project documentation.

## Getting Started

Follow these steps to run the AarogyaNiketan application locally.

### Prerequisites

- **Java 1.8** or later
- **Maven** 3.6 or later
- **MySQL** or **PostgreSQL**: Ensure you have a database set up and running.
- **Git**: For cloning the repository.

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/harissssssss/AarogyaNiketanApp.git
   cd AarogyaNiketanApp
   
2. **Configure the database:**

Update your application.properties file with the appropriate database configuration. For example, for MySQL:
```bash
spring.datasource.url=jdbc:mysql://localhost:3306/your_database
spring.datasource.username=your_username
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
```

Or for PostgreSQL:
```bash
spring.datasource.url=jdbc:postgresql://localhost:5432/your_database
spring.datasource.username=your_username
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
```

3. **Buil The Project:**
```bash
mvn clean install
```
4. **Run The Application:**
```bash
mvn spring-boot:run
```

#Using Swagger UI
Once the application runs, you can use Swagger UI to explore the REST APIs.

Open your web browser and navigate to:
```bash
http://localhost:8080/swagger-ui/


