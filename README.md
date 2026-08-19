# 🗂️Comandos usados no MySQL e suas funções:

- mysql -u root
Função: Acessa o MySQL usando o usuário root.

- CREATE DATABASE escola_db;
- Função: Cria um novo banco de dados chamado escola_db.
- SHOW DATABASES;
- Função: Mostra todos os bancos de dados existentes no MySQL.
- CREATE TABLE alunos (...);
- Função: Cria uma tabela chamada alunos, com as colunas matricula, nome e cpf.
- INSERT INTO alunos (matricula, nome, cpf) VALUES (1, 'Jose Maria', '12312312312');
- Função: Insere um novo aluno na tabela alunos.
- SELECT * FROM alunos;
- Função: Mostra todos os registros e todas as colunas da tabela alunos.
- asterisco* ;
- Função: Traz todas as colunas existentes
- WHERE;
- Função: É o filtro para não trazer a tabela inteira
- DELETE;
- Função: Ele deleta informações no banco de dados
- UPDATE
- Função: Modificar dados que já existem dentro de uma tabela
- PRIMARY KEY;
- Função: É uma coluna ou grupo de colunas que serve como um identificador único para cada linha de uma tabela
# ⚠️Importante:
- Sempre terminar os códigos com ;
- antes de criar a tabela, normalmente você precisa selecionar o banco


# 🦶Passo a Passo:

passo 1: Usar o comando - mysql -u root para entrar no servidor

passo 2: Construir uma estrutura (Nesse caso para uma escola) 

- Usando CREATE TABLE alunos (
    matricula INT,
    nome VARCHAR(50),
    cpf VARCHAR(11)
);
- CREATE é o comando de construção
- INT são os números inteiros
- VACHAR e o limete de caracteres

  passo 3: Inserindo dados usando INSERT INTO alunos(matricula, nome, cpf) Values (1, 'Rafaela Souza', '12345678900');

  passo 4: Hora de consultar os dados inseridos usando SELECT * FROM alunos; ou se esta buscando algo especifico use SELECT nome FROM alunos Where matricula =1;
