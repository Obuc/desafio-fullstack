![Logotipo OBUC Tech](./logo_tech.png)

# 🤓 Desafio Desenvolvedor Full Stack Júnior Obuc
Seja bem-vindo(a)! Nessa etapa gostaríamos de conhecer melhor a sua criatividade e suas habilidades, avaliando  sua capacidade técnica como candidato(a) à vaga de Desenvolvedor Full-stack Júnior.

## Instruções
- Criar um repositório a partir desse modelo;
- Codificar sua solução.
- Atualizar o arquivo `readme.md` com o passo a passo para rodar sua aplicação localmente.
- Após finalizar, você irá enviar o link do seu repositório (não se esqueça de deixá-lo público) para o requisitante do teste.
- Prazo: 5 dias corridos após o recebimento. Você pode enviar a solução incompleta/parcial.

## Aplicação Proposta
Você deverá desenvolver uma aplicação web/mobile(opcional) para gerenciar tarefas domésticas, com possibilidade de designar tarefas a diferentes membros da família. O desafio está separado em duas etapas:

### Back-end
Desenvolva uma API utilizando Node.js e Typescript que contenha as seguintes rotas:
-  `/register` - [POST] - esta rota deve cadastrar um usuário;
- `/login` - [POST] - esta rota deve autenticar um usuário;
- `/tasks` - [POST] - esta rota deve cadastrar uma nova tarefa. (requer autenticação);
- `/tasks/{id}` - [PUT] - esta rota deve editar a tarefa com o ID especificado. Parâmetros sugeridos para o corpo da requisição: nome da tarefa, ID do usuário que  fará a tarefa, status (não iniciada, em andamento, concluída). Tarefas concluídas não podem ser editadas. (requer autenticação);
- `/tasks` - [GET] - esta rota deve retornar a lista de todas as tarefas, com possibilidade de filtro de status da tarefa (não iniciada, em andamento, concluída). (requer autenticação);
- `/tasks/{id}` - [GET] - esta rota deve retornar a tarefa com o ID especificado com todos os seus dados  (requer autenticação);
- `/tasks/{id}` - [DELETE] - esta rota deve deletar a tarefa especificada.

### Front-end
Desenvolva uma aplicação web utilizando **React Native** que atenda às seguintes histórias:
 - Eu como usuário desejo me cadastrar;
 - Eu como usuário desejo realizar login;
 - Eu como usuário autenticado desejo visualizar todas as tarefas;
 - Eu como usuário autenticado desejo filtrar todas as tarefas não-iniciadas/em andamento/concluídas;
 - Eu como usuário autenticado desejo visualizar os detalhes de uma tarefa;
 - Eu como usuário autenticado desejo criar uma tarefa;
 - Eu como usuário autenticado desejo editar uma tarefa.
 - Eu como usuário autenticado desejo apagar uma tarefa.

A aplicação deve ser responsiva a diferentes tamanho de tela. Ela deve **obrigatoriamente** consumir os dados da API desenvolvida na etapa anterior.

## Diferenciais
Será um diferencial se você também fizer:
- Deploy em qualquer ambiente de nuvem;
- Criação de testes unitários e de integração;
- Configurar a aplicação também como mobile para rodar dentro de um emulador Android.

> **Observações:**
> - Você pode utilizar o banco de dados de sua preferência (relacional ou não relacional).
> - A estilização e design do front-end/app ficam a seu critério.
> - Framework sugerido para a aplicação backend: NestJs; mas você pode usar o de sua preferência.


## Links que podem ajudar 
- [Criar um repositório a partir de um modelo](https://docs.github.com/pt/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template#creating-a-repository-from-a-template)
- [React Native · Learn once, write anywhere](https://reactnative.dev/)
- [NestJS - A progressive Node.js framework](https://nestjs.com/)
