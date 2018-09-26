## MVC and EF

### Scaffolding (Reverse Data Model)
```
Scaffold-DbContext "Server=(localdb)\mssqllocaldb;Database=Blogging;Trusted_Connection=True;" Microsoft.EntityFrameworkCore.SqlServer -OutputDir Models
```
see: https://docs.microsoft.com/en-us/ef/core/get-started/aspnetcore/existing-db?view=aspnetcore-2.1

#### EF CORE Initial Create - Migrations

How to 'update-database' with initial migrations history
https://stackoverflow.com/questions/43687433/update-database-command-is-not-working-in-asp-net-core-entity-framework-6-beca


### Viewmodels

How to design
see: https://stackoverflow.com/questions/9881790/how-to-design-viewmodel

Binding dynamic views
https://www.wiliam.com.au/wiliam-blog/asp-net-mvc-5-view-model-collection-binding

Passing params
https://andrewlock.net/passing-variables-to-a-view-component/


### Identity
https://docs.microsoft.com/en-us/aspnet/core/security/authentication/scaffold-identity?view=aspnetcore-2.1&tabs=visual-studio
https://stackoverflow.com/questions/50749519/windows-authentication-asp-net-core-2-database-role-authorization  (windows auth for auth - roles from db)
