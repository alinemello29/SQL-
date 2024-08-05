MANIPULAÇÃO
Declarações
4 minutos
O código abaixo é uma declaração SQL. Uma declaração é um texto que o banco de dados reconhece como um comando válido. As declarações sempre terminam em ponto e vírgula ;.

CREATE TABLE table_name (
   column_1 data_type, 
   column_2 data_type, 
   column_3 data_type
);

Vamos analisar os componentes de uma declaração:

CREATE TABLEé uma cláusula . Cláusulas realizam tarefas específicas em SQL. Por convenção, cláusulas são escritas em letras maiúsculas. Cláusulas também podem ser chamadas de comandos.
table_namerefere-se ao nome da tabela à qual o comando é aplicado.
(column_1 data_type, column_2 data_type, column_3 data_type)é um parâmetro . Um parâmetro é uma lista de colunas, tipos de dados ou valores que são passados ​​para uma cláusula como um argumento. Aqui, o parâmetro é uma lista de nomes de colunas e o tipo de dados associado.
A estrutura das instruções SQL varia. O número de linhas usadas não importa. Uma instrução pode ser escrita toda em uma linha, ou dividida em várias linhas se isso facilitar a leitura. Neste curso, você se familiarizará com a estrutura de instruções comuns.

Instruções
Checkpoint 1 Passed
1 .
Vamos dar uma olhada mais de perto na declaração que escrevemos antes. No editor de código, digite:

SELECT * FROM celebs;

Execute o código para observar os resultados e pergunte-se:

Quais partes da declaração são cláusulas ?
Em qual tabela estamos aplicando o comando?
Descubra a dica para ver as respostas e depois prossiga para o próximo exercício.