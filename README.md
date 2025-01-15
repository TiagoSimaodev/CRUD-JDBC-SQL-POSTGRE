 GERENCIADOR DE USUARIOS E TELEFONES - PROJETO JDBC COM POSTGRESQL 
 * Este é um projeto simples desenvolvido em Java, utilizando JDBC para conexão com o banco de dados PostgreSQL. 
 * O objetivo do projeto é gerenciar usuários e seus telefones, utilizando operações CRUD (Create, Read, Update, Delete).

FUNCIONALIDADES:

CRUD PARA USUÁRIOS:
* Adicionar usuários com ID, Nome e E-mail.
* Atualizar informações dos usuários.
* Consultar usuários cadastrados.
* Excluir usuários.

CRUD PARA TELEFONES:
* Adicionar telefones associados aos usuários pelo usuariopessoa.
* Atualizar informações dos telefones.
* Consultar telefones cadastrados.
* Excluir telefones.
* Estrutura do Banco de Dados
* O banco de dados é composto por duas tabelas:

TABALE USUARIOS:
* id (PRIMARY KEY)
* nome
* email

TABELA TELEFONES:
* id (PRIMARY KEY)
* numero
* tipo
* usuariopessoa (FOREIGN KEY que referencia a tabela usuarios)


TECNOLOGIAS UTILIZADAS:
* Java
* JDBC
* PostgreSQL
* JUnit


COMO EXECUTAR:
* Clone este repositório.
* Configure o banco de dados PostgreSQL com as tabelas necessárias.
* Atualize o arquivo de configuração JDBC com suas credenciais de acesso ao banco.
* Crie uma classe chamada TesteBanco, utilizando as anotações @Test do JUnit, para realizar a execução dos métodos CRUD.
* Compile e execute o projeto em sua IDE ou terminal.

MELHORIAS FUTURAS:
* Implementação de interface gráfica (Swing ou JavaFX).
* Adição de testes automatizados mais robustos.
* Criação de relatórios.
