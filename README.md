# Trazabilidad-Lotes

Proyecto: Sistema de Trazabilidad de Lotes de Palta (MVP)
Stack: ASP.NET Core (MVC), EF Core, SQL Server

## Instrucciones rápidas
1. Configurar connection string en `src/TrazabilidadApp/appsettings.json`
2. Desde `src/TrazabilidadApp`:
   - `dotnet tool install --global dotnet-ef` (si es necesario)
   - `dotnet ef migrations add InitialCreate`
   - `dotnet ef database update`
   - `dotnet run`
