# Estruturas de Dados e Algoritmos



## Estrutura de dados

Estrutura organizada de dados na memória de um computador (ou dispositivo de armazenamento) de forma que os dados possam ser utilizados corretamente.

Algumas são altamente especializadas.

Usando as estruturas adequadas através de algoritmos, podemos trabalhar com uma grande quantidade de dados, como aplicações em bancos de dados e serviços de busca.



## Algoritmo

Conjunto de instruções estruturadas e ordenadas para realizar uma tarefa específica. São utilizadas para manipular dados nas estruturas (inserir, buscar, excluir e ordenar).

**Operações básicas:** Inserir dados, excluir, localizar um elemento, percorrer todos os itens da estrutura para visualização, classificar/ordenar (ordem numérica, alfabética, etc...).

**Principais estruturas:** Vetores e matrizes (Arrays), registro, lista, pilha, árvore, tabela hash e grafos.



****



## Arrays

Estruturas de dados simples que podem auxiliar quando há muitas variáveis do mesmo tipo.

- **Vetor:** Unidimensional. Possui um índice que começa no zero.
- **Matriz:** Multidimensional. Vetor de vetores.



****



## Registros

Formato especializado de armazenamento que pode armazenar mais de um tipo de dado. é composto por campos que especificam cada uma das informações que a compõem.

Toda estrutura de registro tem um nome (ex.: livro) e pode ser acessada por meio do operador ponto.

Exemplo: _livro_.preco



****



## Listas

Listas possuem tamanhos ajustáveis, enquanto arrays são fixos.

- **Listas Ligadas -** Possui nós que conhecem o valor armazenado neles mesmos e no próximo elemento. Os nós estão amarrados.

  O último nó é o último até que seja adicionado outro.

  A lista é manipulada durante a execução do algoritmo e é variável.

- **Lista Duplamente Ligada -** Bidimensional. Tem ligação com o valor anterior **e** posterior. Permite navegação reversa.



****



## Pilha (ou Stack)

Tem acesso restrito - somente um item pode ser lido ou removido por vez.

- **LIFO (ou UEPS) -** LIFO (Last In First Out) / UEPS (Último que Entra Primeiro que Sai): O primeiro elemento a ser retirado é o último que tiver sido inserido.
- **FIFO (ou PEPS) -** FIFO (First In First Out) / PEPS (Primeiro que Entra Primeiro que Sai): O primeiro elemento a ser retiado é o primeiro que tiver sido inserido.



****



## Filas

Segue o conceito **FIFO/PEPS**: o primeiro a ser removido é também o primeiro que foi inserido.



****



## Árvore

Estrutura organizada com elementos colocados em forma hierárquica, onde existe o elemento que fica no topo da árvore (**raiz**) e seus elementos subordinados (**nós**/**folhas**).

Divide a estrutura de uma maneira que a raiz é sempre o meio, facilitando na busca.



****



## Tabela Hash/Espalhamento/Dispersão

Associa as chaves de pesquisa a valores. É uma generalização do Array, mas utiliza a função _hashing_.

- **Hashing -** Espalha os elementos os deixa desordenados dentro do "array" que define a tabela.
- **Valores -** Posição/índice em que o elemento se encontra.
- **Chave -** Parte da informação que compõe o elemento a ser manipulado.

Espalhar facilita a busca, pois permite acesso rápido de uma posição do "array" através da chave.

A tabela hash sabe exatamente qual é a chave.



****



## Grafos

Estruturas que permitem programar a relação entre objetos. Os objetos são **vértices**/**nós** dos grafos. Os relacionamentos são **arestas**.



****

