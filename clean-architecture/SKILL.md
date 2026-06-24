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
