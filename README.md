# .NET Fina

To run instance of database, use docker:

`docker run -e "ACCEPT_EULA=Y" -e "MSSQL_SA_PASSWORD=#YourPassword#" --name sqlserver  -p 1433:1433 -d mcr.microsoft.com/mssql/server:2022-latest`

To execute database migrations do you need install **[.NET Core CLI](https://learn.microsoft.com/en-us/ef/core/cli/dotnet)** and execute the commands below

First `dotnet ef migrations add v1` after `dotnet ef database update`

The Swagger is implement on API

![image](https://github.com/user-attachments/assets/f2710d0f-8d1c-4a22-85c8-162d4be3304a)

The web application with Blazor and MudBlazor

### Categories list

![image](https://github.com/user-attachments/assets/d2e75302-87f2-45f5-8f56-9327b0ff1896)

### Delete dialog

![image](https://github.com/user-attachments/assets/adb50f9a-79e0-43b1-9eeb-625c6b55aa06)

### Create category page

![image](https://github.com/user-attachments/assets/844b6419-c0b8-49e3-b299-7ebf8142aba5)
