# Fullstack Challenge

Você está preparado?

## Descrição

Nós gostariamos de entender um pouco mais de você. Não tenha medo de errar. Isso não é uma questão de certo ou errado. Apenas dê o seu melhor. Boa sorte! :)

## Table of Contents

- [Goal](#goal)
- [Non-functional specs](#non-functional-specs)
- [User Stories](#user-stories)
- [Business Rules](#business-rules)
- [Deliverables](#deliverables)
- [Evaluation](#evaluation)

## Goal

Estamos em 2103 e a humanidade se deparou novamente com um cenário nada agradável que há anos não presenciava. Um novo virus está presente e foi classificado como uma Pandemia Mundial: COVID-20.
Nossa equipe foi acionada para desenvolver uma aplicação para que os especialistas de saúde possam ver ver os dados dos agentes patogênicos, como vírus e bacterias. Isso ajudará a ter um histórico mais preciso e a encontrar o tratamento.
Sua tarefa é criar uma RESTful API e telas capazes de registrar essas informações.


## Non-functional specs

* Backend deve ser criado em .NET.
* Frontend deve ser criado com Angular.
* Você pode escolher entre os bancos de dados SQL Server ou Oracle.
* Você pode usar qualquer outra tecnologia que você acha necessario ou legal.
* De o seu melhor.


## User Stories

* Como um usuário anônimo, eu gostaria de cadastrar um registro de um agente patogênicos (Nome, Foto, Posição Geografica do inicio da infecção, tipo de agente).
* Como um usuário anônimo, eu gostaria de cadastrar o histórico da evolução do agente patogênico contendo a informação de quantidade de mortes e quantidade de infectados. Por exemplo. Em 01/01/2103, o vírus Covid-20 teve 0 mortes e 1 infectado. Em 07/01/2103, o mesmo vírus teve 1.000 mortes e 10.000 infectados. A ideia é como se fosse um uma tabela de histórico.
* Como um usuário anônimo, eu gostaria de ver uma lista de registros dos agentes patogênicos.
* Como um usuário anônimo, eu gostaria de poder filtrar a lista de registro dos agentes patogênicos por nome.
* Como um usuário anônimo, eu gostaria de poder filtrar a lista de registro dos agentes patogênicos que comecaram a infeçao em um raio de 1000 km dada uma posição.
* Como um usuário anônimo, eu gostaria de poder atualizar um registro de agente patogênico.
* Como um usuário anônimo, eu gostaria de poder visualizar um gráfico da evolução do agente patogênico.
* Como um usuário anônimo, eu gostaria de poder deletar um registro de agente patogênico e todo o seu registro do sistema.


### Business Rules

* A aplicação não tem sistema de autenticação e de permissão. Haverá apenas usuários anônimos. Isso pois a aplicação é um MVP.
* Categorias devem ser apenas "Vírus", "Bacterias", "Fungos" e "Protozoários".


## Deliverables

* O código fonte em um git repository público.
* Um live demo público.
* OpenAPI 3.0 document.
* Instruções de como executar o ambiente de desenvolvimento.
* Instruções de como realizar o deploy.
* Postman collection.


## Evaluation

* Boas práticas.
* Manutenção de código.
* Performance.
* Escabilidade.
