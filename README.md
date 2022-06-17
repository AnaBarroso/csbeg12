# csbeg12
Passo a Passo:
1.	 Download e rodar instalador Node.js no link: https://nodejs.org/en/download/

2.	 Instalar React com o comando: npm install react react-dom

3.	 Instalar Adonis com o comando: npm i -g @adonisjs/cli

4.	- Download e rodar Instalador Postgres no Link: https://www.enterprisedb.com/downloads/postgres-postgresql-downloads


5.	Download e rodar Instalador Pgadmin4 no Link: https://www.pgadmin.org/download/pgadmin-4-windows/ (Caso utilizando Windows)

Obs:  No passo 3 e 4 Setar a senha master do Postgres como "123" e a porta 5432 ou alterar as configurações nos arquivos de configuração de conexão com o banco de dados (database.js e .env).

6.	- Criar uma database com o nome "imobil" (ou também mudar nome nas configurações dos arquivos).

7.	- Rodas as migrations com o comando: adonis migration:run

8.	- Executar o back-end no diretório "Projeto" com o comando: Adonis serve –dev

9.	- Executar o front-end no diretório "Front" com o comando: npm start

10.	- Consultar o arquivo "Routes.js" para ver as rotas implementadas que podem ser utilizadas.

11.	- Consultar o arquivo "modelo_json.json" para ver alguns modelos de dados necessários para utilizar os services implementados nos controllers.

12.	- Fazer as requisições com as rotas desejadas passando os dados como parâmetros (Analisar a porta que está rodando o backend no localhost)

13.	Exemplos gerados no Postman:
- Criar pessoa: 127.0.0.1:3333/pessoa?cpf=129854&nome=fulano&sexo=M

- Criar usuário: 127.0.0.1:3333/signup?pessoa_id=1&username=admin&email=admin@csbeg.com&password=1234&permissao=cliente
