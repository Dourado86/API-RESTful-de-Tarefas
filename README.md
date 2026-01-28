# API-RESTful-de-Tarefas
API RESTful desenvolvida em **.NET 8**, utilizando **Entity Framework Core** e **SQL Server**, com foco em boas práticas de arquitetura e organização de código.

## 🛠️ Tecnologias utilizadas
- .NET 8
- ASP.NET Core Web API
- Entity Framework Core
- SQL Server (LocalDB)
- Swagger / OpenAPI
- Injeção de Dependência (DI)

## 📐 Arquitetura
- Controllers
- DTOs (Data Transfer Objects)
- Repository Pattern
- DbContext (EF Core)
- Migrations para versionamento do banco

## 📌 Funcionalidades
- Criar tarefa
- Listar tarefas
- Buscar tarefa por ID
- Atualizar tarefa
- Remover tarefa

## 🔄 Endpoints principais
- `GET /api/tasks`
- `GET /api/tasks/{id}`
- `POST /api/tasks`
- `PUT /api/tasks/{id}`
- `DELETE /api/tasks/{id}`

## ▶️ Como executar o projeto
1. Clonar o repositório
2. Configurar a connection string no `appsettings.json`
3. Executar as migrations:
   ```bash
   dotnet ef database update

