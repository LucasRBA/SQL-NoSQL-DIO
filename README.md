# SQL-NoSQL-DIO
## O Papel dos Bancos de Dados SQL e NoSQL na Engenharia de Dados
### Bancos de dados SQL e NoSQL
#### SQL(“Structured Query Language”), ou seja os bancos de dados relacionais, são utilizados quando se sabe precisamente as proporções do projeto em questão, normalmente um projeto que não sofrerá mudanças grandes ao longo do tempo.
####  NoSQL (“Not Only SQL”)  surgiu como uma alternativa ao modelo relacional e não para tentar substituí-lo. Tal necessidade veio principalmente pela necessidade de escalabilidade, ou seja, suporta  grandes quantidades de requisições.
####  No modelo SQL utiliza-se linguagem de consulta estruturada e possuem esquema pré-definido. Nos DBs NoSQL existem esquemas dinâmicos para dados sem estrutura pré-definida(não-estruturados).
####  De forma geral, em grandes empresas são utilizadas ambas soluções, além de garantir maior segurança também se garante que as necessidades serão atendidas da melhor maneira, se utilizando por exemplo o SQL para cadastros de clientes e NoSQL para imagens, comentários e demais informações no caso de um “e-commerce”.
####  Já o modelo NoSQL é comumente utilizado para dados não estruturados como documentos ou JSON, mas não se limitando apenas a essas estruturas.
####  É recomendado sempre ter em mente as regras de negócio do empreendimento ao qual o banco de dados será implementado, pois, caso sejam necessários relacionamentos entre diversas entidades, já se sabe que um DB SQL será necessário, porém com menos de mil consultas diárias, utilizar uma solução paga e robusta como Oracle é desperdício de recurso computacional e dinheiro.
####  Databases(DBs) SQL são verticalmente escaláveis sendo necessário maior uso de recursos, ou instalação de ainda mais  hardware no computador em questão , ao contrário dos bancos de dados NoSQL  que por sua vez podem ser escalados horizontalmente não necessitando de um hardware superior num primeiro momento.
####  Assim como o SQL é baseado em tabelas e tem como princípio teórico a matemática de conjuntos desenvolvida por Venn e Euler e resolvem diversos cenários do mundo real com  maestria podendo citar, sistemas bancários, sistemas de saúde, principalmente.
####  As soluções NoSQL, focam em agilidade e simplicidade de armazenar diferentes formas de dados, sem relacionamento, porém não quer dizer que não possam ser tipos de dados complexos. 
####  Podendo citar como principais usos: armazenamentos de documentos, chave-valor, grafos e/ou colunas. (Ex: MongoDB para Documentos, Redis para chave-valor, Cassandra para Colunas e Neo4j para Grafos)
### Considerações sobre engenharia de dados
#### Para que um engenheiro de dados possa de forma eficiente arquitetar de forma eficiente toda a estrutura que será posteriormente utilizada por um cientista de dados e deles retirar “insights” que ajudem a direcionar futuras decisões de mercado. São necessários alguns passos, dentre eles:
 - Obter conhecimento dos dados da empresa e suas origens afim de realizar a ingestão de dados em “datawarehouses” e “datalakes”;
 - Saber das necessidades, prioridades, e tipos de estratégias que a empresa visa por em prática;
 - Construir um bom ETL/ELT , assim deixando apenas dados úteis no pipeline (sanitizar os dados);
 - Definir quais tipos de dados serão utilizados pelos usuários, e naquele cenário específico quais tipos de ferramentas serão mais produtivas (Power BI,Tableau, Python com Pandas, Numpy, entre oputros).
#### Num mundo onde Terabytes de conteúdo são gerados em minutos, analisar e se basear em dados para tomar decisões de mercado, é além de uma riqueza, sobretudo uma necessidade.
####  Seja o conteúdo utilizado proveniente de um DB SQL ou NoSQL, o mais importante não é a fonte, nem tipos de dados, e sim o tratamento correto, desde a limpeza dos dados, até a realização das análises que podem gerar riquezas incalculáveis a seus detentores e ajudar uma instituição a se manter com bons números no mercado.
