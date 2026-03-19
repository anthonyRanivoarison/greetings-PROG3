# Getting Started — Building a RESTful Web Service

A hands-on Spring Boot project following the official Spring guide
[Building a RESTful Web Service](https://spring.io/guides/gs/rest-service),
done as a first introduction to Spring Boot in the context of our PROG3 course.

---

## What I learned

- Setting up a Spring Boot project from scratch
- Creating a REST controller with `@RestController`
- Handling request parameters with `@RequestParam`
- Returning JSON responses automatically with Spring
- Understanding the basics of the Spring MVC architecture

---

## How to run
```bash
./mvnw spring-boot:run
```

Then open your browser or use curl:
```bash
curl "http://localhost:8080/greeting?name=Antonio"
```

Expected response:
```json
{
  "id": 1,
  "content": "Hello, Jean!"
}
```