# Atividade-Desenvolvedor-PHP
<b>Exercicio</b>
<br>
Banco de dados utilizado Mysql
<br>
Comandos utilizados para a criação do banco e tabela.
<br>
CREATE DATABASE cliente;<br>
USE cliente;<br>
CREATE TABLE pessoa(<br>
 idPessoa int auto_increment not null primary key,<br>
 nome varchar(150) not null,<br>
 data_nascimento date not null,<br>
 cpf varchar (11) not null,<br>
 sexo char(2) not null,<br>
 fone varchar(50) not null,<br>
 email varchar(100) not null<br>
);

