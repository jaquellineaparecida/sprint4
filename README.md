# Grupo: URSA

Sistema de Recomendação de Livros
Descrição do Projeto
Este projeto é uma API RESTful desenvolvida em .NET Core para gerenciar um sistema de recomendação de livros. A API permite realizar operações CRUD (Criar, Ler, Atualizar, Excluir) tanto para livros quanto para autores. A arquitetura adotada é monolítica e utiliza o padrão de design Repository para acesso a dados.


# Como executar o projeto 

Aqui está um tutorial sobre como realizar builds das pipelines do projeto e executar o projeto na nuvem.



## Passo a Passo

 - Primeiro, é preciso criar uma infraestrutura no Portal do Azure. Crie um grupo de recursos para um serviço de aplicativo e um banco de dados.
 - Em seguida, execute a pipeline de Build.
 - Depois, execute a pipeline de Release com o nome do serviço de aplicativo que foi criado.
- Retorne ao banco de dados no Azure, utilize a string de conexão e insira-a na aplicação, para que o nosso banco na nuvem esteja conectado à aplicação.
- Para acessar o Swagger e realizar os testes, vá até a URL do serviço de aplicativo criado e adicione **/swagger/index.html** no final.
    
    **Exemplo:** https://swaggersprint4.azurewebsites.net/swagger/index.html

- Agora é só realizar os testes e as persistências no banco de dados.
- Utilize este vídeo como apoio: https://youtu.be/h47wOQuUvCM?si=ULgoVXuLqeytUawu
