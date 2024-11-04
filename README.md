- 👋 Hi, I’m Ruslana
- 🖥️ I’m a Java and Spring Boot software developer 
- 🌱 I’m currently honing my programming skills
- 📫 Contact: https://linkedin.com/in/ruslanaprus
- 📖 Proficient languages: 🇺🇦 Ukrainian 🇬🇧 English 🇵🇱 Polish

:cat: **My Projects**:

| Project Title & Repository                                                                                 | Purpose                                                                                                                                                                     | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | Tools & Technologies                                                                                        |
| ---------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------- |
| [Travel Management System](https://github.com/ruslanaprus/goit-academy-dev-hw13)<br><br>Oct 21 -><br>Nov 3 | A Java-based web app managing clients, planets, and tickets using PostgreSQL. Supports CRUD operations with Thymeleaf for HTML rendering and Hibernate ORM for data access. | - Provides backend services to manage clients, planets, and tickets through HTTP.<br>- DAO layer is used to manage database transactions.<br>- DTO pattern is used for fetching and presenting a subset of entity attributes.<br>- The `IGenericService` interface and `GenericService` class define reusable CRUD methods that can handle any type of entity.<br>- `TicketService` uses Hibernate Query Language to execute custom queries for data fetching by joining multiple tables and selecting specific fields.<br>- Servlet is used to translates HTTP requests into service calls following the MVC design pattern.<br>- Thymeleaf templates to render responses. | Java 21, Hibernate ORM, Flyway, Thymeleaf, Jakarta Servlet, PostgreSQL, Docker, Gradle                      |
| [Cattivity Time](https://github.com/ruslanaprus/goit-academy-dev-hw11)<br><br>Oct 10 -><br>Oct 19          | A simple Java servlet app that displays time in a selected time zone together with a cat image. Uses cookies to remember previously selected time zone.                     | - Returns pictures of the cute cats.<br>- Uses HttpFilter checking requests to `/time` endpoint to validate `timezone` parameter.<br>- Uses `Thymeleaf` to render response pages (for both success and error).<br>- You can deploy the application using Docker with the official Tomcat 10 image from Docker Hub.                                                                                                                                                                                                                                                                                                                                                          | Java 21, Jakarta Servlet, Tomcat, Thymeleaf, SLF4J, Logback, JUnit, Mockito, Gradle, Docker, GitHub Actions |
