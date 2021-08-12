# Desafio NGINX com NodeJS :game_die:
FullCycle
Curso: DEVOPS
Módulo: 1. Docker

### Descrição do desafio :pencil2:
Nesse desafio você colocará em prática o que aprendemos em relação a utilização do nginx como proxy reverso. A idéia principal é que quando um usuário acesse o nginx, o mesmo fará uma chamada em nossa aplicação node.js. Essa aplicação por sua vez adicionará um registro em nosso banco de dados mysql, cadastrando um nome na tabela people.

O retorno da aplicação node.js para o nginx deverá ser:

<h1>Full Cycle Rocks!</h1>

- Lista de nomes cadastrada no banco de dados.

Gere o docker-compose de uma forma que basta apenas rodarmos: docker-compose up -d que tudo deverá estar funcionando e disponível na porta: 8080.

Suba tudo em um repositório e faça a entrega.

 
### INSTRUÇÕES :pushpin:
```
git clone https://github.com/GabrielCayres1/Desafio-NGINX-NODEJS-MYSQL.git

cd desafio-docker-nginx-node-mysql

docker-compose up [-d]
```
<br/>
<br/>
