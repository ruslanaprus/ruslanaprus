# 👋 Hi, I’m Ruslana
- 🖥️ I’m a Java Software Engineer 
- 🌱 I’m currently honing my programming skills
- 📫 Contact: https://linkedin.com/in/ruslanaprus
- 📖 I speak 🇺🇦 Ukrainian 🇬🇧 English 🇵🇱 Polish

## Languages and tools
<div align="center">
  <code><img width="50" src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/java.png" alt="Java" title="Java"/></code>
  <code><img width="50" src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/spring.png" alt="Spring" title="Spring"/></code>
  <code><img width="50" src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/rest.png" alt="REST" title="REST"/></code>
  <code><img width="50" src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/git.png" alt="Git" title="Git"/></code>
  <code><img width="50" src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/postgresql.png" alt="PostgreSQL" title="PostgreSQL"/></code>
	<code><img width="50" src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/sqlite.png" alt="SQLite" title="SQLite"/></code>
  <code><img width="50" src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/junit.png" alt="JUnit" title="JUnit"/></code>
	<code><img width="50" src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/mocikto.png" alt="mocikto" title="mocikto"/></code>
  <code><img width="50" src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/postman.png" alt="Postman" title="Postman"/></code>
  <code><img width="50" src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/swagger.png" alt="Swagger" title="Swagger"/></code>
	<code><img width="50" src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/http.png" alt="HTTP" title="HTTP"/></code>
  <code><img width="50" src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/c++.png" alt="C++" title="C++"/></code>
	<code><img width="50" src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/html.png" alt="HTML" title="HTML"/></code>
	<code><img width="50" src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/css.png" alt="CSS" title="CSS"/></code>
</div>

## :cat: **My Projects**:

### [Note Manager with REST API](https://github.com/ruslanaprus/goit-academy-dev-hw19)

A Java Spring application that provides a REST API and website for **notes management**. The purpose of this application is to provide an interface for managing notes, which handles user authentication, session management, account lockout mechanisms, and input validation. The application has two independent parts:

- **MVC Module**: Handles traditional web-based interactions.
- **REST API Module**: Offers standardised endpoints for integration with external systems.

Both modules share a centralised architecture for core functionalities, including JPA repositories, services, database entities, and caching, ensuring consistency and reusability.

• Java 21 • Spring Boot • Spring Data JPA • Spring Security • JWT • PostgreSQL • Flyway • Jakarta Bean Validation • Thymeleaf • JUnit 5 • Mockito • Springdoc OpenAPI •

<details>
<summary>Details of the project</summary>
<br>
  
**REST API**: CRUD endpoints for managing notes with operations like `GET`, `POST`, `PUT`, `DELETE`.

- Query-based **searching** to locate notes **by a keyword**.
- Data frequently **reused within a request** (e.g., fetched user details) is **temporarily cached**.

**Security:**

- Each user's notes are **isolated and private**.
- New users can sign up via `/api/v1/signup`.
- Endpoints `/api/v1/signup` and `/api/v1/login` are publicly accessible, while all other endpoints require authentication.
- Stateless architecture is implemented with **JWT authentication** for secure token-based sessions.
- Passwords are hashed using a secure `PasswordEncoder` implementation.
- Failed login attempts are tracked, with accounts locked temporarily after 3 unsuccessful login attempts.

**Database:**

- Managed with **Spring Data JPA** and **PostgreSQL**.
- **Flyway** handles schema migrations and initial data seeding.

**Open API Documentation:** Provides interactive Swagger UI for testing endpoints.

**Web Application:**

- Implements user-friendly navigation using the **Thymeleaf** template engine.
- Provides forms for login, signup, and note operations with dynamic content rendering.
</details>

---
### [Travel Management System](https://github.com/ruslanaprus/goit-academy-dev-hw13)

A Java-based web app managing clients, destinations, and tickets using PostgreSQL. Supports CRUD operations with Thymeleaf for HTML rendering and Hibernate ORM for data access.

• Java 21 • Hibernate ORM • Flyway • Thymeleaf • Jakarta Servlet • Tomcat •  PostgreSQL • Docker • Gradle •

<details>
<summary>Details of the project</summary>
<br>
  
- Provides backend services to manage clients, planets, and tickets through HTTP.
- DAO layer is used to manage database transactions.
- DTO pattern is used for fetching and presenting a subset of entity attributes.
- The `IGenericService` interface and `GenericService` class define reusable CRUD methods that can handle any type of entity.
- `TicketService` uses Hibernate Query Language to execute custom queries for data fetching by joining multiple tables and selecting specific fields.
- Servlet is used to translate HTTP requests into service calls following the MVC design pattern.
- Thymeleaf templates to render responses.

</details>


---
### [Cattivity Time](https://github.com/ruslanaprus/goit-academy-dev-hw11)

A simple Java servlet app that displays time in a selected time zone together with a cat image. Uses cookies to remember previously selected time zone.

• Java 21 • Jakarta Servlet • Tomcat • Thymeleaf • SLF4J • Logback • JUnit • Mockito • Gradle • Docker • GitHub Actions •

<details>
<summary>Details of the project</summary>
<br>

- Returns pictures of the cute cats.
- Uses HttpFilter checking requests to `/time` endpoint to validate `timezone` parameter.
- Uses `Thymeleaf` to render response pages (for both success and error).
- You can deploy the application using Docker with the official Tomcat 10 image from Docker Hub.

</details>

---


### [Status Code Cats Web Server](https://github.com/ruslanaprus/goit-academy-dev-hw09)

A simple web server that serves images representing different HTTP status codes. These images are fetched from the `https://http.cat` API or served from a local cache.

• Java 21 • `http.cat` API • SLF4J • Logback • ttf font •

<details>
<summary>Details of the project</summary>
<br>

- This is an exercise in web server implementation based on `com.sun.net.httpserver.HttpServer`.
- Before downloading images from `http.cat` API, the application sends a **HEAD** request to ensure the image exists at the source.
- For image handling optimization, caching is implemented at two levels:
    1. **In-Memory Caching**: To minimize file system access and API calls, recently requested images are stored as `CachedImage` objects, which include the image bytes and a timestamp.
    2. **File System Caching**: Before fetching an image from the remote API, the file system is checked for a locally stored copy to avoid repeated downloads.
- During the download, images are written to temporary files to avoid partial downloads in case of network errors.
- Added custom cat-like fonts as a cute extra feature.

</details>

---

### [SQL Database Manager with REST API and Flyway Integration](https://github.com/ruslanaprus/goit-academy-dev-hw08)

This project extends the functionality of the original [SQL Database Operations Manager](https://github.com/ruslanaprus/goit-academy-dev-hw07) by introducing several significant new features, including database migrations using Flyway, implementation of CRUD operations for Workers, Clients, and Projects, and a flexible HTTP server to handle client requests for database communication.

• Java 21 • JDBC • PostgreSQL • SQLite • Jackson • Flyway • HikariCP • SLF4J • Logback • Dropwizard Metrics • JUnit • Mockito •

<details>
<summary>Details of the project</summary>
<br>

- Used Flyway Gradle Plugin for DB migrations.
- Used **Template Method Pattern** to implement `AbstractGenericService`. The class works as a template and provides methods that represent steps for CRUD operations (preparing statements, executing queries, handling result sets) that vary by entity type, so they are implemented in subclasses.
- Created 2 mappers: `EntityMapper` - to map domain objects to SQL statements and vice versa, isolating SQL interactions from business logic, and `JsonEntityMapper` - to handle JSON data conversion, allowing the API to send and receive JSON-formatted data.
- `MyHttpServer` handles HTTP requests by checking the HTTP method (`GET`, `POST`, `PUT`, `DELETE`) and routing the request to the appropriate service method. Includes error handling for unsupported methods (405), missing resources (404), invalid requests (400).
- `HttpServerFactory` registers context paths (endpoints) for each service, enabling the API to expose different resources (e.g., `/client`, `/worker`). In this way, each service operates within a defined context path to provide clear routing based on resource type.

</details>

---
