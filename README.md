# Projeto Teste Seguro Auto Zurich

Backend: O projeto foi desenvolvido no Visual Studio 2022 com .NET 6.0, linguagem C# e banco de dados SQL Server. A criação do banco e o acesso aos dados foi feito utilizando Entity Framework Core com migrations.

Para rodar, seguir os seguintes passos:
1) Abrir a solution no Visual Studio 2022
2) Alterar a connection string nos arquivos appsettings.json dos projetos Zurich.SeguroAuto.Infra e Zurich.SeguroAuto.Api
3) Executar as migrations pelo gerenciador de pacotes (dotnet ef database update)
4) Executar o Json server na pasta jsonserver pelo command
   * npm install -g json-server (caso ainda não esteja instalado)
   * json-server --watch db.json
5) Executar projeto Zurich.SeguroAuto.Api

Frontend: O projeto foi desenvolvido em Angular em Visual Studio Code

Para rodar, seguir os seguintes passos:
1) Abrir o projeto no VS Code
2) Instalar pacotes pelo terminal (npm install)
3) Executar (ng serve)
