# Create API Endpoint (.NET)

## Prompt

```
Create a .NET API endpoint with the following specification:

- **HTTP Method**: [GET | POST | PUT | PATCH | DELETE]
- **Route**: [e.g. /api/products/{id}]
- **Description**: [What this endpoint does]
- **Request Body** (if applicable): [Description or JSON schema]
- **Response**: [Description or JSON schema]
- **Authentication**: [None | JWT | API Key | Role: ...]

Requirements:
- Follow RESTful conventions.
- Include proper input validation using FluentValidation or DataAnnotations.
- Return appropriate HTTP status codes (200, 201, 400, 404, 500, etc.).
- Add XML documentation comments.
- Use MediatR/CQRS if the project already uses that pattern; otherwise use a service layer.
- Include any relevant DTOs, commands, queries, and handlers.
```
