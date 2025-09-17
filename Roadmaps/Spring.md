## Spring Core

Spring IoC / Dependency Injection (DI)

Constructor Injection

Setter Injection

Field Injection (@Autowired, @Inject)

Bean Scopes (singleton, prototype, request, session, etc.)

Bean Lifecycle & Callbacks (@PostConstruct, @PreDestroy)

ApplicationContext vs BeanFactory

@Component, @Service, @Repository, @Controller

@Configuration & @Bean

@Qualifier, @Primary, @Lazy

@Value (Injecting properties)

--
## Spring AOP (Aspect-Oriented Programming)

Aspect, Advice, JoinPoint, Pointcut

@Aspect, @Before, @After, @Around, @AfterReturning, @AfterThrowing

Proxy-based AOP (JDK vs CGLIB)

Use-cases: Logging, Security, Transactions, Caching

--
## Spring Data Access

JDBC Template

NamedParameterJdbcTemplate

Exception Translation

Transactions

Programmatic vs Declarative (@Transactional)

Propagation, Isolation, Rollback rules

DataSource configuration

ORM integration (Hibernate / JPA)

EntityManager

Repositories

Spring Data JPA

--
## Spring MVC

DispatcherServlet

Controllers

@Controller vs @RestController

@RequestMapping, @GetMapping, @PostMapping, etc.

Request Parameters

@RequestParam, @PathVariable, @RequestBody, @RequestHeader, @CookieValue

Model & View

Model, ModelAndView

@ModelAttribute

View Resolvers (JSP, Thymeleaf)

Binding & Validation (@Valid, BindingResult, Validator interface)

Exception Handling

@ExceptionHandler

@ControllerAdvice

Interceptors (HandlerInterceptor)

File Uploads (MultipartFile)

--
## Spring Boot Basics

Spring Boot Auto-Configuration

Starter dependencies (spring-boot-starter-web, spring-boot-starter-data-jpa, etc.)

Spring Boot Application structure (@SpringBootApplication)

Application properties (application.properties / application.yml)

Embedded servers (Tomcat, Jetty)

Running Spring Boot applications

Spring Boot DevTools, Profiles, Logging

--
## Spring REST

@RestController & JSON APIs

@RequestBody & @ResponseBody

ResponseEntity

Exception Handling in REST APIs

HATEOAS basics

Versioning APIs

CORS configuration

--
## Spring Security

Authentication & Authorization

UserDetailsService

PasswordEncoder (BCryptPasswordEncoder)

In-memory vs JDBC vs Custom UserDetails

Security configuration (WebSecurityConfigurerAdapter / SecurityFilterChain)

Role-based access control

JWT (JSON Web Tokens) integration

CSRF, CORS basics

--
## Spring Data & Database Integration

Spring Data JPA

CrudRepository, JpaRepository, PagingAndSortingRepository

Custom queries (@Query, JPQL, NativeQuery)

Transactions with @Transactional

Caching with Spring Cache

Spring Data MongoDB (optional if using NoSQL)

QueryDSL / Specifications (advanced)

--
## Spring Testing

Unit testing with JUnit & Mockito

@SpringBootTest

@WebMvcTest

@DataJpaTest

TestRestTemplate & MockMvc

Integration Testing with Embedded DB (H2)

--
## Spring Advanced

Spring Profiles

Property sources & @PropertySource

Conditional beans (@ConditionalOnProperty, @ConditionalOnMissingBean)

Event handling (@EventListener, ApplicationEventPublisher)

Scheduling (@Scheduled, TaskScheduler)

Async processing (@Async, AsyncResult, Executor)

Spring Actuator (monitoring & metrics)

Spring Cloud / Microservices basics (optional)

--
## Spring Integration with Other Tech

Thymeleaf templates

File uploads / downloads

Email sending (JavaMailSender)

WebSockets

Kafka / RabbitMQ integration (messaging)

RestTemplate / WebClient (consuming APIs)

OpenAPI / Swagger integration
