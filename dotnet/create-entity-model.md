# Create Entity Model (.NET)

## Prompt

```
Create a .NET entity model with the following specification:

- **Entity Name**: [e.g. Product]
- **Description**: [What this entity represents]
- **Properties**: [List each property with its type and any constraints]
- **Relationships**: [One-to-many, many-to-many, etc. with other entities]
- **Schema/Table name** (optional): [e.g. Products]

Requirements:
- Use C# record or class as appropriate.
- Add Entity Framework Core configurations (Fluent API or Data Annotations).
- Include audit fields (CreatedAt, UpdatedAt) if the project uses them.
- Add any domain logic or value objects as needed.
- Include the EF Core DbSet registration in the DbContext.
```
