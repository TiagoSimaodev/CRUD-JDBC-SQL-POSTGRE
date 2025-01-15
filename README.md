Gerenciador de Usuários e Telefones - Projeto JDBC com PostgreSQL
Este é um projeto simples desenvolvido em Java, utilizando JDBC para conexão com o banco de dados PostgreSQL. O objetivo do projeto é gerenciar usuários e seus telefones, utilizando operações CRUD (Create, Read, Update, Delete).

Funcionalidades
CRUD para Usuários:

Adicionar usuários com ID, Nome e E-mail.
Atualizar informações dos usuários.
Consultar usuários cadastrados.
Excluir usuários.
CRUD para Telefones:

Adicionar telefones associados aos usuários pelo usuariopessoa.
Atualizar informações dos telefones.
Consultar telefones cadastrados.
Excluir telefones.
Estrutura do Banco de Dados
O banco de dados é composto por duas tabelas:

Tabela usuarios:

id (PRIMARY KEY)
nome
email
Tabela telefones:

id (PRIMARY KEY)
numero
tipo
usuariopessoa (FOREIGN KEY que referencia a tabela usuarios)
Tecnologias Utilizadas
Java
JDBC
PostgreSQL
JUnit
Como Executar
Clone este repositório.
Configure o banco de dados PostgreSQL com as tabelas necessárias.
Atualize o arquivo de configuração JDBC com suas credenciais de acesso ao banco.
Crie uma classe chamada TesteBanco, utilizando as anotações @Test do JUnit, para realizar a execução dos métodos CRUD.
Compile e execute o projeto em sua IDE ou terminal.
Melhorias Futuras
Implementação de interface gráfica (Swing ou JavaFX).
Adição de testes automatizados mais robustos.
Criação de relatórios.
