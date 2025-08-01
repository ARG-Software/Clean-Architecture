# A Pragmatic Clean Architecture Template 🏗️

This template is a production-ready .NET 8 application using **Pragmatic Clean Architecture (PCA)** and **Domain-Driven Design (DDD)** principles.

This template is designed to be **scalable**, **testable**, and **easy to maintain**—perfect for real-world applications.

---

## ⚙️ Architecture Overview

The solution is divided into clearly separated layers:

- `Bookify.Domain` – Core business logic and domain models
- `Bookify.Application` – Use cases and application logic (CQRS, validation)
- `Bookify.Infrastructure` – External dependencies (EF Core, logging, etc.)
- `Bookify.Presentation` – API layer (controllers, filters, etc.)
- `Bookify.ArchitectureTests`, `Bookify.Application.UnitTests`, etc. – Complete test coverage across layers

**Patterns & Tools:**
- ✅ CQRS with [MediatR](https://github.com/jbogard/MediatR)
- ✅ Validation via [FluentValidation](https://fluentvalidation.net/)
- ✅ Authentication using [Keycloak](https://www.keycloak.org/) (JWT)
- ✅ Persistence with EF Core
- ✅ Logging with Serilog
- ✅ Integration and unit testing
- ✅ Architecture validation tests

---

## 🎯 Why Use This Template?

- **Maintainable**: Clear separation of concerns with firm architectural boundaries.
- **Scalable**: Designed to evolve with your business needs.
- **Practical**: Applies Clean Architecture without overengineering.

> Learn more in our article:  
> [Taming the Chaos: A Developer’s Guide to Pragmatic Clean Architecture in .NET ⚡](https://arg-software.medium.com/taming-the-chaos-a-developers-guide-to-pragmatic-clean-architecture-in-net-%EF%B8%8F-c0b05de359a7)

---

## 🚀 Getting Started

1. **Clone the repository**  
   ```bash
   git clone https://github.com/ARG-Software/Clean-Architecture.git

2. Open the solution in Visual Studio, Rider, or VS Code.

3. Set `Bookify.Presentation` as the startup project.

4. **Run the project**
   ```bash
   dotnet run --project src/Bookify.Presentation
   ```

5. Explore and extend based on your domain and requirements.

---

## 📦 Project Breakdown

| Project | Description |
|---------|-------------|
| `Bookify.Domain` | Core business rules and domain entities |
| `Bookify.Application` | Use cases, DTOs, CQRS handlers, validators |
| `Bookify.Infrastructure` | Data access, external services, logging |
| `Bookify.Presentation` | ASP.NET Core Web API layer |
| `Bookify.Application.UnitTests` | Unit tests for the Application layer |
| `Bookify.ArchitectureTests` | Enforces architectural rules and layer isolation |

---

## 🧠 Learn More

- 📝 Read the architecture blog post
- 🔍 Browse all ARG Software projects

---

## 🧑‍💼 About ARG Software

We build modern, maintainable software using pragmatic approaches to architecture and design.

Visit us at 🌐 [arg.software](https://arg.software)

---

## 📄 License

This project is licensed under the MIT License.



