//mostra todos os possiveis modelo de projetos
dotnet new

https://github.com/TryCatchLearn/DatingApp

//Criar certificado valido para localhost
dotnet dev-certs https --trust

//Criar as classes de migração fo first code do entity
dotnet ef migrations add InitialCreate -o Data/Migrations

//atualizar a base de dados com o migrations
dotnet ef database update

git status

git init
 
dotnet new gitignore

adicionar ao .gitignore o arquivo appsettings.json