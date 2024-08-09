MANIPULAÇÃO
Selecione
3 minutos
SELECTinstruções são usadas para buscar dados de um banco de dados. Na instrução abaixo, SELECTretorna todos os dados na namecoluna da celebstabela.

SELECT name FROM celebs;

1. SELECTé uma cláusula que indica que a declaração é uma consulta. Você usará SELECTsempre que consultar dados de um banco de dados.
2. nameespecifica a coluna da qual consultar dados.
3. FROM celebsespecifica o nome da tabela da qual consultar dados. Nesta declaração, os dados são consultados da celebstabela.

Você também pode consultar dados de todas as colunas em uma tabela com SELECT.

SELECT * FROM celebs;

*é um caractere curinga especial que temos usado. Ele permite que você selecione cada coluna em uma tabela sem precisar nomear cada uma individualmente. Aqui, o conjunto de resultados contém cada coluna na celebstabela.

SELECTAs instruções sempre retornam uma nova tabela chamada conjunto de resultados .

Instruções
Checkpoint 1 Passed
1 .
Vamos dar uma olhada mais de perto SELECTe recuperar todos os names na celebstabela. No editor de código, digite:

SELECT name FROM celebs; 

Ponto de verificação 2 aprovado
2 .
Exclua sua SELECTdeclaração anterior do editor de código.

Para SELECT todos os dados na celebstabela, insira a seguinte instrução no editor de código usando o *caractere curinga:

SELECT * FROM celebs;