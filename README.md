# nomeProvisorio

## 1. Introdução
Atualmente no Brasil existem mais de 10 plataformas de streaming de filmes e series, cada uma com seu catálogo exclusivo, sendo assim fornecendo uma variedade de conteúdo a seus usuários, porém para um brasileiro classe média ou baixa, acaba ficando muito difícil de assinar todos os produtos oferecidos sem que sua renda não sofra uma avaria. Para evitar a pirataria uma boa opção é optar por uma ou duas plataformas que possuem um catálogo que o agrade mais. Mas como ele pode saber dentre essas várias opções qual combina mais com seu gosto?
Com o intuito de sanar essa dúvida, uma aplicação que compara os gêneros escolhidos pelo usuário e os gêneros de cada plataforma, numerando e demonstrando ao usuário qual plataforma tem um catálogo que o agrade mais.

## 2. Fundamentação Teórica
Nesta seção, aborda-se o conceito web bot e uma breve explicação sobre Sistemas de Recomendação.

### 2.1 Web Bot
O web bot tem como sua função buscar por palavras chave pré definidas pelo sistema e retornar o resultado encontrado, sua utilização pode ser feita para diversas funçoes, para a aplicação desse projeto sera necessaria para coletar o catalogo de plataformas que não possuem sua api propria.

### 2.2 Sistemas de Recomendação
Com a expansão dos serviços sem fio, o número de usuários móveis aumentou rapidamente e a quantidade de informações na internet e no meio sem fio também aumentou exponencialmente. Essa quantidade de informações torna-se difícil de ser monitorada pelos usuários, pois a busca por dados específicos pode custar muito em termos de tempo. Além disso, no cenário móvel, apenas funções simples de pesquisa e navegação estão disponíveis devido ao poder de computação limitado de um telefone móvel. Portanto, é mais preferível deixar que as informações desejáveis encontrem os clientes, em vez de deixá-los pesquisar informações específicas quando necessário (Amer A. Sallam. Global Trends in Computing and Communication Systems, 2011, Adaptado).

## 3. Metodologia e Métodos
Nesta seção apresentam-se  os  procedimentos  metodológicos  adotados  neste  trabalho.

### 3.1 Coleta de Dados
Para o desenvolvimento deste trabalho será necessário coleta de duas fontes, Usuário e as plataformas de Streaming, Pós a coleta de dados, o sistema utilizara da ideia de sistema de recomendação de pegar as categorias escolhidas pelo usuário, e compará-la com o número de vezes em que essa categoria aparece no catálogo das plataformas disponíveis, assim escolhendo dentre elas a mais interessante ao usuário.

### 3.1.1 Coleta de dados do Usuário
Para a Coleta de dados do usuário será necessário por parte do usuário inserir suas categorias de filmes e series.

### 3.1.2 Coleta de dados das Plataformas
Para a coleta de dados da plataforma será necessário usar a api de cada plataforma, caso a plataforma não possua uma api própria como a Netflix, será necessário um web bot para coletar o catalogo e categorizando-os.

## 4. PROPOSTA DE SOLUÇÃO(Conclusão)
Nesta proposta apresenta-se uma ideia de através da aplicação de machine learning junto com sistema de recomendação, pegar dados inseridos pelo usuário e compará-lo com 
o catálogo de cada plataforma, retornando assim uma lista indicando qual plataforma atendera mais seu gosto.

## Referencias
- Estudo comparativo de Algoritmos de Recomendação https://bcc.ime.usp.br/tccs/2014/marcost/monografia_final.pdf
- Amazon.com Recommendations http://www.cs.umd.edu/~samir/498/Amazon-Recommendations.pdf
- Global Trends in Computing and Communication Systems https://link.springer.com/chapter/10.1007/978-3-642-29219-4_30
- https://www.cnnbrasil.com.br/tecnologia/2020/03/09/servicos-de-streaming-conheca-as-novas-plataformas-que-chegam-ao-brasil
- https://exame.com/tecnologia/netflix-prime-video-e-disney-quanto-custa-assinar-streaming-no-brasil/
