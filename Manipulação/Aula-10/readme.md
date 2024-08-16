MANIPULAÇÃO
Restrições
6 minutos
Restrições que adicionam informações sobre como uma coluna pode ser usada são invocadas após especificar o tipo de dados para uma coluna. Elas podem ser usadas para dizer ao banco de dados para rejeitar dados inseridos que não aderem a uma certa restrição. A declaração abaixo define restrições nacelebstabela.

CREATE TABLE celebs (
   id INTEGER PRIMARY KEY, 
   name TEXT UNIQUE,
   date_of_birth TEXT NOT NULL,
   date_of_death TEXT DEFAULT 'Not Applicable'
);

1. PRIMARY KEYcolunas podem ser usadas para identificar exclusivamente a linha. Tentativas de inserir uma linha com um valor idêntico a uma linha já na tabela resultarão em uma violação de restrição que não permitirá que você insira a nova linha.

2. UNIQUEcolunas têm um valor diferente para cada linha. Isso é similar a, PRIMARY KEYexceto que uma tabela pode ter muitas UNIQUEcolunas diferentes.

3. NOT NULLcolunas devem ter um valor. Tentativas de inserir uma linha sem um valor para uma NOT NULLcoluna resultarão em uma violação de restrição e a nova linha não será inserida.

4. DEFAULTAs colunas recebem um argumento adicional que será o valor assumido para uma linha inserida se a nova linha não especificar um valor para essa coluna.

Instruções
Checkpoint 1 Passed
1 .
Crie uma nova tabela com restrições nos valores. No editor de código, digite:

CREATE TABLE awards (
   id INTEGER PRIMARY KEY,
   recipient TEXT NOT NULL,
   award_name TEXT DEFAULT 'Grammy'
);

Quantas tabelas você vê no esquema do banco de dados à direita?