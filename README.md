# nomeProvisorio

## 1. Introdução
Atualmente no Brasil existem mais de 10 plataformas de streaming de filmes e series, cada uma com seu catálogo exclusivo, sendo assim fornecendo uma variedade de conteúdo a seus usuários, porém para um brasileiro classe média ou baixa, acaba ficando muito difícil de assinar todos os produtos oferecidos visto que atualmente custa por volta de 309,72[Exame] reais para assinar todas as plataformas. Para evitar a pirataria uma boa opção é optar por uma ou duas plataformas que possuem um catálogo que o agrade mais. Mas como ele pode saber dentre essas várias opções qual combina mais com seu gosto?
Com o intuito de sanar essa dúvida, uma aplicação que compara os gêneros escolhidos pelo usuário e os gêneros de cada plataforma, numerando e demonstrando ao usuário qual plataforma tem um catálogo que o agrade mais.

## 2. Fundamentação Teórica
Nesta seção, aborda-se o conceito web bot e uma breve explicação sobre Sistemas de Recomendação.

### 2.1 Web Bot
O web bot tem como sua função buscar por palavras chave pré definidas pelo sistema e retornar o resultado encontrado, sua utilização pode ser feita para diversas funçoes, para a aplicação desse projeto sera necessaria para coletar o catalogo de plataformas que não possuem sua api propria. "Um Web bot, também denominado Internet robot, Web agent ou smart agent, é uma ferramenta de software que realiza tarefas específicas na Web, geralmente de forma autônoma, seguindo a estrutura de hiperlinks de acordo com um algoritmo específico"(Elsevier B.V, Knowledge-Based Systems 2021, Adaptado).

### 2.2 Sistemas de Recomendação
"Com a expansão dos serviços sem fio, o número de usuários móveis aumentou rapidamente e a quantidade de informações na internet e no meio sem fio também aumentou exponencialmente. Essa quantidade de informações torna-se difícil de ser monitorada pelos usuários, pois a busca por dados específicos pode custar muito em termos de tempo. Além disso, no cenário móvel, apenas funções simples de pesquisa e navegação estão disponíveis devido ao poder de computação limitado de um telefone móvel. Portanto, é mais preferível deixar que as informações desejáveis encontrem os clientes, em vez de deixá-los pesquisar informações específicas quando necessário" (Amer A. Sallam. Global Trends in Computing and Communication Systems, 2011, Adaptado).

## 3. Metodologia e Métodos
Nesta seção apresentam-se os procedimentos metodológicos adotados neste trabalho.

### 3.1 Coleta de Dados
Para o desenvolvimento deste trabalho será necessário coleta de duas fontes, Usuário e as plataformas de Streaming, Pós a coleta de dados, o sistema utilizara da ideia de sistema de recomendação de pegar as categorias escolhidas pelo usuário, e compará-la com o número de vezes em que essa categoria aparece no catálogo das plataformas disponíveis, assim escolhendo dentre elas a mais interessante ao usuário.

### 3.1.1 Coleta de dados do Usuário
Para a Coleta de dados do usuário será necessário por parte do usuário inserir suas categorias de filmes e series.

### 3.1.2 Coleta de dados das Plataformas
Para a coleta de dados da plataforma será necessário usar a api de cada plataforma, caso a plataforma não possua uma api própria como a Netflix, será necessário um web bot para coletar o catalogo e categorizando-os.

## 4. PROPOSTA DE SOLUÇÃO
Nesta proposta apresenta-se uma ideia de através da aplicação de um sistema de recomendação, pegar dados inseridos pelo usuário e compará-lo com 
o catálogo de cada plataforma disponivel no Brasil, retornando assim uma lista indicando qual plataforma atendera mais seu gosto.

## Referencias
- Marcos M. Takahashi(2015) **Estudo comparativo de Algoritmos de Recomendação** Disponivel em: <<https://bcc.ime.usp.br/tccs/2014/marcost/monografia_final.pdf>> Bacharelado,Universidade de São Paulo
- csUmd(2003) **Amazon.com Recommendations** Disponivel em: <<http://www.cs.umd.edu/~samir/498/Amazon-Recommendations.pdf>>
-  Springer(2011) **Global Trends in Computing and Communication Systems** Disponivel em: <<https://link.springer.com/chapter/10.1007/978-3-642-29219-4_30>>
- ScienceDirect(2021) **Knowledge-Based Systems** Disponivel em: <<https://www.sciencedirect.com/journal/knowledge-based-systems>>
- cnn(2020)  **Serviços de streaming: conheça as novas plataformas que chegam ao Brasil** Disponivel em: <<https://www.cnnbrasil.com.br/tecnologia/2020/03/09/servicos-de-streaming-conheca-as-novas-plataformas-que-chegam-ao-brasil>>
- Exame(2020) **Quanto custa assinar todos os principais serviços de streaming do mercado?** Disponivel em: <<https://exame.com/tecnologia/netflix-prime-video-e-disney-quanto-custa-assinar-streaming-no-brasil/>>
