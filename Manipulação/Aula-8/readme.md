MANIPULAÇÃO
Atualizar
3 minutos
A UPDATEinstrução edita uma linha em uma tabela. Você pode usar a UPDATEinstrução quando quiser alterar registros existentes. A instrução abaixo atualiza o registro com um idvalor de 4para ter o twitter_handle @taylorswift13.

UPDATE celebs 
SET twitter_handle = '@taylorswift13' 
WHERE id = 4; 

1. UPDATEé uma cláusula que edita uma linha na tabela.
2. celebsé o nome da tabela.
3. SETé uma cláusula que indica a coluna a ser editada.

twitter_handleé o nome da coluna que será atualizada
@taylorswift13é o novo valor que será inserido na twitter_handlecoluna.
4. WHEREé uma cláusula que indica qual(is) linha(s) atualizar com o novo valor da coluna. Aqui, a linha com um 4na idcoluna é a linha que terá o twitter_handleatualizado para @taylorswift13.

Instruções
Checkpoint 1 Passed
1 .
Atualize a tabela para incluir o identificador do Twitter de Taylor Swift . No editor de código, digite:

UPDATE celebs 
SET twitter_handle = '@taylorswift13' 
WHERE id = 4; 

SELECT * FROM celebs;