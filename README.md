# :game_die: Banco de Dados:
 
 Um banco de dados é uma coleção de dados relacionados, são fatos que podem ser gravados e que possuem um significado implícito.
 
# Data Base Management System ou Sistema Gerenciador de Banco de Dados (SGBD):
 
Software especializado e desenvolvido especialmente para *gerenciar* essas coleções de dados de uma forma segura. É uma coleção de programas que permitem o usuário criar e manter um banco de dados facilitando os processos de definição, construção, manipulação e compartilhamento de banco de dados entre vários usuários e aplicações.

### :hammer_and_wrench: Construção:
- Processo de armazenar em uma mídia adequada e controlada pelo SGBD.

### :file_folder: Manipulação:
- Inclui funções como pesquisas em um Banco de Dados para recuperar ou buscar algum dado específico, atualizar o Banco de Dados e gerar relatórios.

### :globe_with_meridians: Compartilhamento:
- Permitir que multiplos usuários acessem, concorrentemente, o Banco de Dados.

## SGBD's relacionais:
- Os SGBDS relacionais são banco de dados que modelam os dados no formato de tabelas, que podem se relacionar entre si. Cada tabela pode possuir diversos atributos, com diversos tipos de dados.
- São mais tradicionais e consolidadas no mercado.
- Exemplos: Oracle, DB2, SQL, Server, Access, PostgreSQL, MySQL, Derby e H2. 

#### Oracle:
- Surgiu no final dos anos 70, com Larry Elliso em conjunto com os co-fundadores da Oracle Corporation, Bob Miner e Ed Oates;
- O banco de dados da Oracle é potente, seguro e tem eficiência para coordenar um grande volume de dados;
- Podendo ser instalado em diversos sistemas operacionais;
- Necessário um hardware potente que possa permitir usufruir de todo desempenho dele.


Os primeiros SGDBs Relacionais apareceram na década de 1980 como uma novidade boa no meio da computação, tanto que esses acabaram sucedendo os bancos de dados hierárquicos em rede predominantes por mainframes.

## SGBD's não relacionais:
- Estes bancos utilizam diversos modelos de dados incluindo documentos, gráficos, chave-valor e colunares. São amplamente reconhecidos pela facilidade em seu desenvolvimento, desempenho escalável, alta disponibilidade e resiliência.
- Conhecidos como NoSQL.
- Exemplos: MongoDB, Redis, Neo4j e Riak.

# Características de um Sistema de Banco de Dados:

- Natureza Autodescritiva;
- Isolamento entre Programa e Dados;
- Múltiplas Visões de Dados;
- Acesso concorrente de múltiplos usuários.


# Transações (fundamental em muitas áreas da computação):
- Uma definição clássica do conceito de transações envolve o acrônimo ACID, oriundo das propriedades de Atomicidade, Consistência, Isolamento e Durabilidade.

<img src="https://github.com/Patricia-Bianca-Lana-Largura/Banco-de-Dados/blob/master/Images/img2.png" width="950">


# O Modelo Relacional:
- Tem uma sólida base formal, construído sob a teoria dos conjuntos, seu nome é devido à relação matemática da teoria dos conjuntos e não aos relacionamentos. Trata-se de um modelo com estruturas de tabelas e alguns conceitos.
- Permite a representação da estrutura lógica do projeto com uma visão genérica. Sua estrutura é feita de uma forma clara e simples, possibilitando representar os dados do mundo real como objetos denominados entidades ou conjuntos de entidades.

<img src="https://github.com/Patricia-Bianca-Lana-Largura/Banco-de-Dados/blob/master/Images/img1.png" width="950">

## Entidade:
- Entidade ou tabela é uma representação gráfica de um conjunto.
### Há 2 tipos de Entidades:
 - Concretas: são objetos do mundo real. Exemplo: carro, computador e funcionário.
 - Abstratas: são intangíveis. Exemplo: aluguel, compra e venda.
 
 ## Atributo:
-  Utilizadas para descrição de entidade, características contidas nas Entidades. Exemplo: uma entidade Cliente pode ser relacionado os atributos, Nome, RG e CPF.

### Tipos de Atributos:
 - Atributo Simples
 - Atributo Multivalorado
 - Atributo Composto
 - Atributo-Chave
 
## Chave Estrangeira (FOREIGN KEY):
 - Trata-se de um campo que aponta para a chave primária de outra tabela.

## Relacionamentos:
- No Modelo Relacional as entidades não podem ficar isoladas, mas sim relacionadas entre si para futuramente ter acesso de forma integrada das informações.

### Tipos de Relacionamentos:
 - Autorrelacionamento
 - Relacionamento Binário
 - Relacionamento Ternário

 ## Cardinalidade:
 - Permite expressar o número de ocorrências com que uma entidade pode tomar parte em um relacionamento, também expressar as possibilidades e restrições de associações entre uma entidade e outra.
 
## Cardinalidade Máxima:
 - Limite máximo de ocorrências em uma entidade para outra.
 
## Tipos:

### Um para Um (1:1)

Ocorre quando a entidade se relaciona com no máximo uma ocorrência.
 
### Um para Muitos (1:N)

Ocorre quando uma entidade se relaciona com muitas ocorrências, mas a ocorrência da outra entidade só se relaciona com uma ocorrência da primeira.

### Muitos para Muitos (N:N) ou (N:M).

Ocorre quando a entidade se relaciona com muitas ocorrências de ambos os lados.

#### Referências: 
>Principais SGBD'S relacionais: [Treina web](https://www.treinaweb.com.br/blog/os-principais-sgbds-relacionais/)

>Conteúdo sobre Transações: [Curso de Banco de Dados MySQL - Curso em Vídeo](https://www.youtube.com/watch?v=Ofktsne-utM&list=PLHz_AreHm4dkBs-795Dsgvau_ekxg8g1r)
