# Dotnet 8 API Boilerplate with MySQL & JWT Auth 

This is a simple barebones API boilerplate that has JWT configured for authentication and database setup with MySQL. As well as all the basic things to get started like Serilog, Rate Limits and Swagger properly configured.

No framework lock-ins, zero abstractions, full control over all the code, only dotnet. Sample controllers are also included for role authorization.

## Features
- MySQL Database with EFCore
- JWT Authentication
- Admin and User roles
- Rate Limit
- Anti-spam Registration
- Swagger UI
- Serilog


## Development

Run initial migrations on first setup:
```
dotnet ef database update
```

Run subsequent migrations:
```
dotnet ef database update
```

To make a new migration:
```
dotnet ef migrations add MigrationName
```

To remove a migration:
```
dotnet ef migrations remove
```

To run the project:
```
dotnet run
```

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
