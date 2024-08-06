MANIPULAÇÃO
Criar
4 minutos
CREATEinstruções nos permitem criar uma nova tabela no banco de dados. Você pode usar a CREATEinstrução sempre que quiser criar uma nova tabela do zero. A instrução abaixo cria uma nova tabela chamada celebs.

CREATE TABLE celebs (
   id INTEGER, 
   name TEXT, 
   age INTEGER
);

1. CREATE TABLEé uma cláusula que informa ao SQL que você deseja criar uma nova tabela.
2. celebsé o nome da tabela.
3. (id INTEGER, name TEXT, age INTEGER)é uma lista de parâmetros que definem cada coluna ou atributo na tabela e seu tipo de dados :

idé a primeira coluna da tabela. Ela armazena valores do tipo de dadosINTEGER
nameé a segunda coluna da tabela. Ela armazena valores do tipo de dadosTEXT
ageé a terceira coluna da tabela. Ela armazena valores do tipo de dadosINTEGER
Instruções
Checkpoint 1 Passed
1 .
Agora que você tem um bom entendimento da sintaxe SQL, podemos criar uma nova tabela. Limpamos o banco de dados dos exercícios anteriores. Confirme que não celebsexiste nenhuma tabela inserindo o seguinte no editor de código:

SELECT * FROM celebs;

Veja os resultados. O banco de dados deve estar vazio!

Ponto de verificação 2 aprovado
2 .
Agora que sabemos que o banco de dados está vazio, vamos criar uma nova celebstabela.

No editor de código, digite:

CREATE TABLE celebs (
   id INTEGER, 
   name TEXT, 
   age INTEGER
); 

Aprenderemos como visualizar esta tabela em um exercício posterior, depois de adicionar alguns dados a ela.