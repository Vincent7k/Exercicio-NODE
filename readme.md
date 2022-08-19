# Exercício cadastrar Novos Usuários no Banco de Dados - NodeJS

### Instale as depêndencias:
1. `npm install express mustache-express dotenv`


### Instale os types
2. `npm install --save-dev @types/express @types/mustache-express @types/node`


### Crie um banco de dados com os seguintes comandos
CREATE DATABASE 'teste'

CREATE TABLE `users` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `name` varchar(100) NOT NULL,
  `age` int(11) NOT NULL DEFAULT 18,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=27 DEFAULT CHARSET=utf8mb4;

### Coloque o nome do banco de dados, usuário e senha no arquivo .env:
- PORT=3000
- MYSQL_DB=teste
- MYSQL_USER=root
- MYSQL_PASSWORD=
- MYSQL_PORT=3306


### Instale o nodemon, mysql e sequelize

3. `npm install -g nodemon typescript ts-node`
4. `npm install mysql2`
5. `npm install sequelize`

Em package.json crie o seu script para rodar o projeto

6. "start-dev": "nodemon -e ts,json,mustache server.ts"

### inicie o projeto com o comando que você criou no script 

npm run start-dev

