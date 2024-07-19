# Fina

To run instance of database, use docker:

`docker run -e "ACCEPT_EULA=Y" -e "MSSQL_SA_PASSWORD=#YourPassword#" --name sqlserver  -p 1433:1433 -d mcr.microsoft.com/mssql/server:2022-latest`

To execute database migrations do you need install **[.NET Core CLI](https://learn.microsoft.com/en-us/ef/core/cli/dotnet)** and execute the commands below

`dotnet ef migrations add v1`
`dotnet ef database update`

The Swagger is implement on API

![image](https://github.com/user-attachments/assets/f2710d0f-8d1c-4a22-85c8-162d4be3304a)
