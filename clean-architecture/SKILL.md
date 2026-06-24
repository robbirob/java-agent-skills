---
name: clean-architecture
description: "Use when reviewing Java applications for Clean Architecture boundaries and framework-free domain logic."
---

# Clean Architecture Enforcer

RULES:
Domain:
- No Spring
- No JPA
- No REST
- No Kafka

Application:
- Use cases
- Ports

Infrastructure:
- Adapter implementations

STOP IMPLEMENTATION IF:
- Domain depends on framework code
