MANIPULAÇÃO
Excluir
2 minutos
A DELETE FROMinstrução exclui uma ou mais linhas de uma tabela. Você pode usar a instrução quando quiser excluir registros existentes. A instrução abaixo exclui todos os registros na celebstabela sem twitter_handle:

DELETE FROM celebs 
WHERE twitter_handle IS NULL;

DELETE FROMé uma cláusula que permite excluir linhas de uma tabela.
celebsé o nome da tabela da qual queremos excluir linhas.
WHEREé uma cláusula que permite que você selecione quais linhas você quer deletar. Aqui queremos deletar todas as linhas onde a coluna twitter_handle IS NULL.
IS NULLé uma condição em SQL que retorna verdadeiro quando o valor é NULLe falso caso contrário.
Instruções
Checkpoint 1 Passed
1 .
Exclua todas as linhas que têm um NULLvalor na coluna twitter handle. No editor de código, digite o seguinte:

DELETE FROM celebs 
WHERE twitter_handle IS NULL;

SELECT * FROM celebs; 

Quantas linhas existem na celebstabela agora?