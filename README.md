# Infentory

This repository contains the starter structure for the **Infentory** project.
It follows a layered architecture with separate folders for API, application
logic, domain entities, infrastructure and shared components.

```
Infentory/
├── src/
│   ├── Infentory.API/                        # HTTP API entry point
│   ├── Infentory.Application/               # UseCase logic, services and DTOs
│   ├── Infentory.Domain/                    # Entities, enums and value objects
│   ├── Infentory.Infrastructure/            # EF, repositories and external services
│   ├── Infentory.Shared/                    # Common tools and base responses
│
├── tests/
│   ├── Infentory.Application.Tests/         # Unit tests
│   ├── Infentory.API.Tests/                 # Integration tests
│
├── docker/
│   ├── Dockerfile                           # API container image
│   ├── docker-compose.yml                   # DB + API orchestration
│
├── build/                                   # CI/CD scripts (optional)
├── Infentory.sln                            # Solution file placeholder
└── README.md
```

The directories currently contain only placeholders and can be filled with
project code as the implementation evolves.
