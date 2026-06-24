---
name: java-spring-review
description: "Use when reviewing Spring Boot Java code for dependency injection, DTO boundaries, validation, logging, transactions, and exception handling."
---

# Spring Boot Review

CHECK:
- Constructor injection only
- No field injection
- DTO separation
- Validation present
- Logging present
- Transaction boundaries clear
- Exceptions handled

FLAG:
- @Autowired fields
- Business logic in controllers
- Entity exposure via REST
