# Create Repository (.NET)

## Prompt

```
Create a repository for the following entity in a .NET project:

- **Entity**: [e.g. Product]
- **Operations needed**: [List CRUD operations and any custom queries required]
- **ORM**: [Entity Framework Core | Dapper | other]
- **Pattern**: [Generic Repository | Specific Repository]

Requirements:
- Define the interface in the Domain/Application layer.
- Implement the repository in the Infrastructure/Persistence layer.
- Use async/await with CancellationToken for all data access methods.
- Register the repository in the DI container (Program.cs or an extension method).
- Include any relevant specifications or query filters if the project uses the Specification pattern.
```
