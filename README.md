# Dio-desefio-de-Projeto-NoSql-
## Neste desafio, você terá a missão de compreender o papel dos Bancos de Dados Relacionais (SQL) e Não Relacionais (NoSQL) no contexto de um Engenheiro de Dados. Para isso, anote todos os conceitos, definições e insights que julgar relevantes em um novo repositório Git, aumentando assim seu portfolio de conhecimentos. Nesse sentido, você pode organizar esse repositório da forma como preferir... Dica: organizar tudo em seu README.md pode ser uma alternativa bem rápida e efetiva, principalmente porque o GitHub provê uma interface bem simples e intuitiva para isso. Bons estudos!

Bancos de Dados Relacionais (SQL) e Não Relacionais (NoSQL)
O que é SQL e NoSQL?
Banco de dados Relacional (SQL): Tipo de banco onde é armazenado informações que tenham relacionamento entre si, utilizado em modelos transacionais, com esquema de dados rígido.

Banco de dados Não Relacional (NoSQL): Surgiram devido a necessidades diferentes, principalmente em escalabilidade horizontal, pois havia necessidade de armazenar volume cada vez maior de informação, principalmente informação não estruturada. O banco não relacional permite manter uma estrutura de dados não rígida.

Tipos de Bancos de dados NoSQL
Existem 4 tipos de bancos de dados NoSQL definidos pela forma como armazenam os dados em suas estruturas, são eles:

Documentos
Grafos
Chave-Valor
Wide Column Store
Documentos:

Um dos tipos mais versáteis que temos no mundo NoSQL, possuindo um schema definido como flexível que permite que os registros e documentos possuam campos com diferentes tipos e em diferentes quantidades sem a existência de um schema fixo. Tais documentos são definidos em formato JSON, utilizando conceitos próximos do modelo Orientado à Objetos onde o objeto aqui equivaleria a um documento. Novos campos podem ser adicionados facilmente, permitindo uma rápida evolução da aplicação em desenvolvimento.

Grafos:

O modelo baseado em estruturas de grafos pode não ser o mais intuitivo, pois os dados são definidos dentro dos nós e vértices, mas permitem a resolução de um tipo específico de queries baseadas em relacionamento.

Chave-Valor:

Bancos do tipo chave-valor são comumente utilizados para sistemas de cache e sessão. Sua estrutura é definida como campos chave mapeados para um objeto muitas vezes não estrutural, em que as consultas somente podem ser realizas pelo campo chave.

Wide Column Store:

Bancos do tipo Wide Column Store utilizam matrizes multi-dimensionais para armazenamento dos dados. São amplamente utilizadas para armazenar quantidades massivas de dados. Os dados são consultados utilizando chaves para cada columna.

Como é Feita a consulta dos dados armazenados no NoSQL?
É importante que sejam definidas as chaves, formas de como deverá ser consultado as informações. A aplicação também deverá saber lidar com a falta de previsibilidade do schema, deverá saber que tipo de informações deverá desprezar e as informações que não poderá desprezar dentro da consulta do banco não relacional.

Sobre DataLake e Databricks
DataLake é um respositório de informações onde pode ser armazenado um grande volume de dados, seja ele estruturado, não estruturados ou semi-estruturado. No ambiente de dados existem minimamente cinco capacidade básicas, são elas: ingestão, armazenamento, processamento, disponibilidade e seguranção das informações. É importante que na arquitetura de um DataLake as cinco capacidade estejam presentes.
