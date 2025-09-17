### Spring Boot 

# Spring Boot Basics

What is Spring Boot & benefits over Spring Framework

@SpringBootApplication annotation

Spring Boot project structure

Starter dependencies (spring-boot-starter-web, spring-boot-starter-data-jpa, etc.)

Spring Boot Auto-Configuration

Embedded servers (Tomcat, Jetty, Undertow)

Running Spring Boot apps (main method, Maven/Gradle run)

Application properties (application.properties / application.yml)

Spring Boot Profiles

Spring Boot DevTools (hot reload, live restart)

--
## Spring Boot Web (REST & MVC)

@RestController vs @Controller

@RequestMapping, @GetMapping, @PostMapping, etc.

Path variables, Request parameters, Request body

ResponseEntity

Exception handling (@ControllerAdvice, @ExceptionHandler)

File upload and download (MultipartFile)

View resolvers (Thymeleaf, JSP)

JSON serialization/deserialization (Jackson integration)

--
## Spring Boot Data & Database

Spring Data JPA integration

CrudRepository, JpaRepository

PagingAndSortingRepository

Entity mapping (@Entity, @Id, @GeneratedValue, @Table)

Relationships (@OneToOne, @OneToMany, @ManyToOne, @ManyToMany)

@Query, JPQL, Native Queries

Transactions (@Transactional)

H2 / MySQL / PostgreSQL integration

Spring Data MongoDB (NoSQL support)

Flyway / Liquibase database migrations

--
## Spring Boot Security

Spring Security integration with Spring Boot

Authentication & Authorization

Password encoding (BCryptPasswordEncoder)

UserDetailsService & custom authentication

Role-based access control

JWT integration for stateless authentication

CSRF & CORS configuration

--
## Spring Boot Advanced Features

Scheduling (@Scheduled, TaskScheduler)

Asynchronous processing (@Async)

Events (@EventListener, ApplicationEventPublisher)

Conditional beans (@ConditionalOnProperty, @ConditionalOnMissingBean)

Profiles-based configuration

Externalized configuration (@Value, @ConfigurationProperties)

Metrics and Monitoring (Spring Boot Actuator)

Logging configuration (Logback, SLF4J)

Health checks & custom endpoints

--
## Spring Boot Testing

Unit testing (@SpringBootTest, @WebMvcTest, @DataJpaTest)

Testing REST APIs with MockMvc / TestRestTemplate

Integration testing with embedded database (H2)

Mockito for mocking dependencies

Test profiles and test properties

Assertions & validation

--
## Spring Boot Integration

RestTemplate / WebClient (consuming external APIs)

Messaging: Kafka / RabbitMQ integration

Email sending (JavaMailSender)

File handling (upload/download)

WebSockets

Swagger / OpenAPI integration for API documentation

Spring Boot + Spring Cloud basics (microservices)
