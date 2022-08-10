# Atividade-Desenvolvedor-PHP
Exercicio 
<br>
Banco de dados utilizado Mysql
<br>
Comandos utilizados para a criação do banco e tabela.
<br>
CREATE DATABASE cliente;
USE cliente;
CREATE TABLE pessoa(
 idPessoa int auto_increment not null primary key,
 nome varchar(150) not null,
 data_nascimento date not null,
 cpf varchar (11) not null,
 sexo char(2) not null,
 fone varchar(50) not null,
 email varchar(100) not null
);

