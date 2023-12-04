![Uploading Screenshot_20231107-060756.png…]()
# AniRealm
*AniRealm* is the ultimate digital domain for manga, manhwa, manhua, and anime enthusiasts!  Embark on a thrilling journey through the boundless universe of illustrated stories and animated adventures. AniRealm is your portal to a mesmerizing multiverse where you can explore, discover, and share your passion for all things manga and anime. Dive into an ever-expanding library of content, featuring the latest releases, timeless classics, and hidden gems from the worlds of manga, manhwa, manhua, and anime. Unleash your curiosity with our fiendishly clever recommendation algorithm, designed to unearth the perfect tales to tantalize your taste buds and ignite your imagination. Engage with fellow aficionados in our vibrant community, where you can discuss your favorite series, debate plot twists, and forge friendships with like-minded souls. Stay connected with the latest news, updates, and events from the realm of illustrated and animated storytelling. AniRealm is your one-stop destination for all your manga and anime cravings. Join us now and unlock the door to a realm of infinite possibilities!

# <h1 align="center"> AniRealm Back-end Application </h1>
___ 
<p align="center">
    <img alt="Java" src="https://img.shields.io/badge/Java->=8-darkblue.svg" />
    <img alt="Maven" src="https://img.shields.io/badge/maven-4.0-brightgreen.svg" />
    <img alt="Spring Boot" src="https://img.shields.io/badge/Spring Boot-3.1.4-brightgreen.svg" />
    <img alt = "GPL v3" src="https://img.shields.io/badge/License-GPLv3-blue.svg" />
    
</p>


---

<p align="left">

## Overview

The AniRealm Backend Application is a robust and scalable Spring Boot-based backend system designed to power a social media platform with features similar to AniRealm. It provides a comprehensive set of RESTful API endpoints for user management, post creation, commenting, liking, and more.

## Technologies Used

- **Framework:** Spring Boot
- **Language:** Java 21
- **Database:** MySQL
- **Build Tool:** Maven
- **Documentation:** SpringDoc OpenAPI (Swagger UI)
- **Email Handling:** JavaMail API



## Dependencies Used

The project utilizes the following dependencies:

- **Spring Boot Starter Data JPA**: Simplifies database access using Spring Data repositories.

- **Spring Boot Starter Web**: Provides support for building web applications, including RESTful APIs.

- **MySQL Connector/J (Runtime Dependency)**: The MySQL JDBC driver for connecting to MySQL databases.

- **Project Lombok (Optional)**: A library for reducing boilerplate code, such as getters and setters.

- **Spring Boot Starter Test (For Testing)**: Provides support for testing Spring Boot applications.

- **Springdoc OpenAPI (Swagger UI)**: Adds Swagger UI for documenting and testing API endpoints.

- **Spring Boot Starter Validation**: Includes validation support for request data binding and response data rendering.

- **JavaMail API**: Used for sending emails.

- **Other Dependencies:** Various other dependencies are included in the `pom.xml` file for specific functionalities, such as Jackson for JSON serialization, Spring Web for web-related features, and more.

Please refer to the project's `pom.xml` file for a comprehensive list of all dependencies and their respective versions.

These dependencies form the foundation of the AniRealm Backend Application, allowing it to deliver robust user management and social media features efficiently.

  ## Dependencies Imported to Spring Initializr


- **Spring Boot Dev Tools:** Spring Boot Dev Tools is used for hot swapping and faster development. It helps in improving the development experience.

  [![Spring Boot Dev Tools](https://img.shields.io/badge/Spring%20Boot%20Dev%20Tools-2.5.5-brightgreen.svg)](https://spring.io/projects/spring-boot)

- **Spring Web:** Spring Web is the core part of the Spring Framework, providing support for building web applications. It's used for handling HTTP requests and responses.

  [![Spring Web](https://img.shields.io/badge/Spring%20Web-5.3.10-brightgreen.svg)](https://spring.io/guides/gs/spring-boot/)

- **Spring Data JPA:** Spring Data JPA simplifies database access with the Java Persistence API (JPA). It provides easy access to data repositories.

  [![Spring Data JPA](https://img.shields.io/badge/Spring%20Data%20JPA-2.5.5-brightgreen.svg)](https://spring.io/projects/spring-data-jpa)

- **MySQL Driver:** MySQL Driver is used for connecting the application to a MySQL database. It allows seamless interaction with the database.

  [![MySQL Driver](https://img.shields.io/badge/MySQL%20Driver-8.0.27-brightgreen.svg)](https://dev.mysql.com/downloads/connector/j/)

- **Lombok:** Lombok is a Java library that helps reduce boilerplate code by automatically generating getters, setters, and other commonly used methods.

  [![Lombok](https://img.shields.io/badge/Lombok-1.18.22-brightgreen.svg)](https://projectlombok.org/)

- **Validation:** The Validation framework provides validation constraints, such as @NotNull, @Size, and @Email, to enforce data integrity.

  [![Validation](https://img.shields.io/badge/Validation-2.0.1-brightgreen.svg)](https://docs.oracle.com/javaee/7/api/javax/validation/constraints/package-summary.html)

- **Swagger:** Swagger is used for API documentation and testing. It provides a user-friendly interface to interact with the RESTful APIs.

  [![Swagger](https://img.shields.io/badge/Swagger-3.0.0-brightgreen.svg)](https://swagger.io/)


## Project Structure

The project follows a clean and organized structure:

- **Main Application Class:** `AniRealmBackendApplication.java` serves as the entry point for the Spring Boot application.
- **Entities:** The application includes entities for `User`, `Post`, `Comment`, and `Like`, each with corresponding repository interfaces.
- **Security Configuration:** Spring Security is employed to secure the application with authentication and authorization.
- **Database Configuration:** The `application.properties` file configures the database connection and Spring Data JPA properties.
- **Controller Classes:** These classes define and document the RESTful API endpoints.

## Screenshots
![Screenshot_20231107-060410](https://github.com/Willow7737/AniRealm/assets/114362590/611ed709-adce-4b2e-8e8b-77e2b3dde24f)
![Screenshot_20231107-055838](https://github.com/Willow7737/AniRealm/assets/114362590/342c58e6-8e71-48b9-83a0-de59f7a7544f)

