# atividade-04-09
CREATE TABLE Aluno_Teste(
  nome varchar(200),
  idade int,
  ra int,
  email varchar(1000),
  endereco varchar (1000)
  );
INSERt into Aluno_Teste (nome, idade, ra, email, endereco) VALUES ('diogo', '19','123','diogo@gmail.com','rua santos do nada');
INSERT into Aluno_Teste (nome, idade, ra, email, endereco) VALUES ('joca','19','132','joca13@hotmail.com','rua jesus pires'); 
INSERT into Aluno_Teste (nome, idade, ra, email, endereco) VALUES ('jose','23','1542','jos3@gmail.com','rua andre martins');
INSERT into Aluno_Teste (nome, idade, ra, email, endereco) VALUES ('mark','21','12234', 'mark@gmail.com','rua washington luis'); 
INSERT into Aluno_Teste (nome, idade, ra, email, endereco) VALUES ('juan','20', '1982', 'ju@n20gmail.com','rua trujilo'); 
 SELECT nome, idade, ra, email, endereco  FROM Aluno_Teste;  
