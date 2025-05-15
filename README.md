# My Spring Boot Learning Path

This outlines my personal learning path for Spring Boot development, focusing on a practical approach.

## Phase 1: Solidify Java Fundamentals

1.  **Review & Practice Java Syntax:**

    - **Resource:** Baeldung article on Java syntax ([https://www.baeldung.com/java-syntax](https://www.baeldung.com/java-syntax)).
    - **Focus:** `switch` statements, loops, operators.
    - **Practice Programs:**
      - Area of a circle calculator (using `double`, `Math.PI`).
      - Fibonacci sequence generator (using `for` loop).
      - User input handler (using `switch` statement).

2.  **Object-Oriented Programming (OOP):**

    - **Concepts:** Encapsulation, Inheritance, Polymorphism, Abstraction.
    - **Practice:** Implement classes for real-world objects (e.g., `Car`, `Animal`, `Product`).
    - **Key Activities:**
      - Class attributes (instance variables).
      - Methods operating on attributes.
      - Inheritance from a base class.
      - Interface implementation.
    - **Example:** `Shape` hierarchy (`Circle`, `Rectangle`, `Triangle`) inheriting from `Shape` and implementing `Calculatable` (calculating area).

3.  **Collections Framework:**

    - **Classes:** `ArrayList`, `LinkedList`, `HashMap`, `HashSet`, `TreeSet`, `TreeMap`.
    - **Practice:**
      - `ArrayList` for storing a list of names.
      - `HashMap` for student IDs and grades.
      - Compare `ArrayList` vs. `LinkedList` performance.

4.  **Exception Handling:**
    - **Keywords:** `try`, `catch`, `finally`, `throw`, `throws`.
    - **Practice:**
      - File reader with `FileNotFoundException`.
      - User input parser with `NumberFormatException`.

## Phase 2: Spring Boot Fundamentals

1.  **Build Tool - Maven:**

    - **Install:** (If needed).
    - **`pom.xml`:** `groupId`, `artifactId`, `version`, `dependencies`.
    - **Dependency Management:** Add/manage dependencies in `pom.xml`.
    - **Maven Commands:** `mvn clean install`, `mvn test`, `mvn package`.

2.  **Spring Framework Core Concepts:**

    - **Dependency Injection (DI):** `@Autowired` annotation.
    - **Inversion of Control (IoC).**
    - **Spring Context:** Bean container.
    - **Beans:** `@Component`, `@Service`, `@Repository`, `@Configuration` annotations.

3.  **Spring Boot:**
    - **Spring Initializr:** ([https://start.spring.io/](https://start.spring.io/)) to create a project.
      - **Dependencies:** `Spring Web`, `Spring Data JPA`, `H2 Database`.
    - **Auto-configuration.**
    - **Starter Dependencies.**

## Phase 3: Building a Simple REST API

1.  **Spring MVC:**

    - **Controllers:** `@RestController` annotation.
    - **Request Mapping:** `@GetMapping`, `@PostMapping`, `@PutMapping`, `@DeleteMapping`.
    - **Request Parameters:** `@RequestParam`, `@PathVariable`, `@RequestBody`.

2.  **REST API Endpoints:**

    - Create endpoints for:
      - Creating (POST)
      - Reading (GET - single and multiple)
      - Updating (PUT/PATCH)
      - Deleting (DELETE)
    - Example: A simple "Todo" application with endpoints for managing todo items.

3.  **Data Persistence (Spring Data JPA):**
    - **JPA Concepts.**
    - **Spring Data JPA Repositories.**
    - **Entities:** Mapping Java classes to database tables with JPA annotations (`@Entity`, `@Id`, `@GeneratedValue`, etc.).
    - **H2 Database:** Configure and use the H2 in-memory database.

## Phase 4: Testing \*\*

1.  **Unit Testing:** JUnit, Mockito.
2.  **Integration Testing:** Testing interactions between components.
3.  **Spring Boot Testing Support:** `@SpringBootTest`.

## Tools & Resources

- **IDE:** VS Code (configured for Java development).
- **Build Tool:** Maven.
- **Baeldung:** ([https://www.baeldung.com/](https://www.baeldung.com/))
- **Spring Boot Documentation:** ([https://spring.io/projects/spring-boot](https://spring.io/projects/spring-boot))
- **Spring Initializr:** ([https://start.spring.io/](https://start.spring.io/))
