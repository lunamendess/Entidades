# Entidades
Existem outras entidades além dessas três?
Sim, Professores
⇨ Quais são os principais campos e tipos?
o id de cada tabela.

⇨ Como essas entidades estão relacionadas?
Estão relacionadas e interligadas pela tabela Cursos.

Comandos do SQL
CREATE DATABASE resilia;
CREATE TABLE cursos(
id int (11) NOT NULL AUTO_INCREMENT,
nome varchar(100) NOT NULL,
PRIMARY KEY(id)
);
CREATE TABLE turmas(
turma_id int (11) NOT NULL AUTO_INCREMENT,
unidade varchar(100) NOT NULL,
turno varchar(100) NOT NULL,
PRIMARY KEY(turma_id)
);
CREATE TABLE alunos(
aluno_id int (11) NOT NULL AUTO_INCREMENT,
nome_aluno varchar(100) NOT NULL,
cpf varchar(13) NOT NULL,
email varchar(20) NOT NULL,
endereço varchar(100) NOT NULL,
telefone varchar(11) NOT NULL,
PRIMARY KEY(aluno_id)
);
CREATE TABLE professores(
professor_id int (11) NOT NULL AUTO_INCREMENT,
nome_professor varchar(100) NOT NULL,
materia varchar(100) NOT NULL,
PRIMARY KEY(professor_id)

);
