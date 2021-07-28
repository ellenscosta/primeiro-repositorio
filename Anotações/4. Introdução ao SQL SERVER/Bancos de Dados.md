# Banco de Dados - Anotações



## Tipos de Bancos de Dados

### Relacionais

Bancos relacionais (SQL) são utilizados em sistemas que requerem uma alta confiabilidade de dados.

Exemplos: SQL SERVER, Oracle, MySQL...

### NoSQL

Os bancos NoSQL servem para uma melhor performance e armazenamento de grandes quantidades de dados. 

Exemplos: MongoDB, Neo4j, Firebase...



****

 ### Chave Primária

Serve como uma forma de identificar um registro único. Gera uma melhor performance nas busca pois vai indexar os registros e retornar uma query de forma mais rápida. 

### Chave Secundária

Faz a relação de uma tabela com outra.

****



## Normalização

**1FN -** Não deve haver um conjunto de colunas repetidos ou mais de uma informação em uma propriedade. 

**2FN -** Não podem existir informações que dependam apenas parcialmente da chave primária.

**3FN - ** Todos os atributos devem depender apenas da chave primária, sendo independentes entre si.



****



