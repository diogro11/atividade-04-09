# atividade-04-09
CREATE TABLE aluno_teste2(
nome varchar (150),
idade int ,
ra varchar (4000),
email varchar (1000),
 endereço varchar (1000)
);
 
insert INTO aluno_teste2(nome, idade, ra, email, endereço) VALUES ('diogo','19','1234','diogo12@gmail.com''rua santos dumont');
insert INTO aluno_teste2(nome, idade, ra, email,endereço) VALUES ('joao','18','12345','joao@hotmail.com','rua valdemir do santos');
insert into aluno_teste2(nome, idade,ra,email,endereço) VALUES ('pedro','20','122321''pedro188@gmail.com''ruagladiador da silva');
insert into aluno_teste2(nome, idade,ra,email,endereço) values ('vitor','20','12321''vic@gmail.com','ruajuventosali');
insert into aluno_teste2(nome, idade,ra,email,endereço) VALUES ('gabriel','23','1233221,'gabs@gmail.com','ruasantosissoai');
                                                                SELECT nome, ra, idade, email, endereço from aluno_teste2;
