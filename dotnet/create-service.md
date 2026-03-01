# Create Service (.NET)

## Prompt

```
Create a service class for the following use case in a .NET project:

- **Service Name**: [e.g. ProductService]
- **Responsibility**: [What business logic this service encapsulates]
- **Dependencies**: [Repositories, other services, external clients, etc.]
- **Methods**: [List each method with input parameters and expected output]

Requirements:
- Define the interface and the implementation separately.
- Use async/await for all I/O operations.
- Handle errors with appropriate exceptions or a Result pattern.
- Register the service in the DI container with the correct lifetime (Scoped | Transient | Singleton).
- Add unit tests for each public method using xUnit and Moq (or NSubstitute).
```
