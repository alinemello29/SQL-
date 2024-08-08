MANIPULAÇÃO
Inserir
7 minutos
A INSERTinstrução insere uma nova linha em uma tabela.

Podemos usar a INSERTdeclaração quando você quiser adicionar novos registros. A declaração abaixo insere um registro para Justin Bieber na celebstabela.

INSERT INTO celebs (id, name, age) 
VALUES (1, 'Justin Bieber', 29);

INSERT INTOé uma cláusula que adiciona a linha ou linhas especificadas.
celebsé a tabela à qual a linha é adicionada.
(id, name, age)é um parâmetro que identifica as colunas nas quais os dados serão inseridos.
VALUESé uma cláusula que indica os dados que estão sendo inseridos.
(1, 'Justin Bieber', 29)é um parâmetro que identifica os valores que estão sendo inseridos.
1: um inteiro que será adicionado à idcoluna
'Justin Bieber': texto que será adicionado à namecoluna
29: um inteiro que será adicionado à agecoluna
Instruções
Checkpoint 1 Passed
1 .
Adicione uma linha à tabela. No editor de código, digite:

INSERT INTO celebs (id, name, age) 
VALUES (1, 'Justin Bieber', 29); 

Olhe para o Database Schema. Quantas linhas há na celebstabela?

Ponto de verificação 2 aprovado
2 .
Adicione mais três celebridades à tabela. Abaixo da sua INSERTdeclaração anterior, digite:

INSERT INTO celebs (id, name, age) 
VALUES (2, 'Beyonce Knowles', 42); 

INSERT INTO celebs (id, name, age) 
VALUES (3, 'Jeremy Lin', 35); 

INSERT INTO celebs (id, name, age) 
VALUES (4, 'Taylor Swift', 33); 

Olhe para o Database Schema. Quantas linhas há na celebstabela agora?