MANIPULAÇÃO
Alterar
3 minutos
A ALTER TABLEinstrução adiciona uma nova coluna a uma tabela. Você pode usar este comando quando quiser adicionar colunas a uma tabela. A instrução abaixo adiciona uma nova coluna twitter_handleà celebstabela.

ALTER TABLE celebs 
ADD COLUMN twitter_handle TEXT;

1. ALTER TABLEé uma cláusula que permite que você faça as alterações especificadas.
2. celebsé o nome da tabela que está sendo alterada.
3. ADD COLUMNé uma cláusula que permite que você adicione uma nova coluna a uma tabela:

twitter_handleé o nome da nova coluna que está sendo adicionada
TEXTé o tipo de dados para a nova coluna
4. NULLé um valor especial em SQL que representa dados ausentes ou desconhecidos. Aqui, as linhas que existiam antes da coluna ser adicionada têm NULLvalores (∅) para twitter_handle.

Instruções
Checkpoint 1 Passed
1 .
Adicione uma nova coluna à tabela. No editor de código, digite:

ALTER TABLE celebs 
ADD COLUMN twitter_handle TEXT; 

SELECT * FROM celebs; 