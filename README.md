# ORACLE-DOTNET-GUIDE

## Criar novo projeto no VS Code
Executar o comando wind+shift+p e digitar .NET: Novo Projeto

## Para se comunicar com o banco de dados Oracle pelo dotnet é necessário instalar:
```
dotnet add package Oracle.ManagedDataAccess
```

## Connection String
```
private readonly string _connectionString = "User Id=USUARIO;Password=SENHA;Data Source=HOST:PORT/DB_NAME";
```
