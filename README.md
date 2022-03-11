<h1>Desafio Business Intelligence proposto pela Alura</h1>

A primeira empresa, Alura Films, necessita analisar dados sobre o IMDB (Internet Movie Database) dos filmes e suas informações. Ela quer saber quais são os filmes mais votados e gêneros mais rentáveis. O percentual de gêneros mais explorados. O dinheiro ganho no filme conforme a estrela do ator. Explorar meta score e IMDB.

Esta análise foi feita em 2 arquivos csv (filmes e posters) e os principais tratamentos de dados que efetuei foi normalizar as informações de algumas colunas da tabela filmes. Por exemplo, a coluna gênero continha diversos valores separados por vírgula para cada filme. Portanto, foi criado uma nova tabela onde cada gênero ficou em linhas separadas da tabela mas mantendo o relacionamento com a tabela de filmes. Além disso, na tabela filmes existiam 4 colunas com nomes dos atores conforme a estrela (1 a 4). Estas colunas foram migradas para uma nova tabela contendo as colunas id do filme, grau da estrela e nome do ator. 

O dashboard com as análises pode ser visualizado em <a href="https://app.powerbi.com/view?r=eyJrIjoiYjVhNGUyZmEtOWRjYS00NGIzLWI3NDAtNmNjZmFjNTRmMTQ3IiwidCI6IjRlOWJkOTMzLTAyOTgtNDdlOC05MDhkLTVlYTI1MTVlNWY1MiJ9&pageName=ReportSectione24e3b5d2949dc7e6ca3">Dashboard Alura Films - Semana 1</a>

A segunda empresa, Alura Food, precisa de um dashboard para analisar o mercado de restaurantes na Índia. A empresa gostaria de saber o total de restaurantes na Índia e a porcentagem dos que possuem serviço de delivery. É importante saber as cidades que mais possuem restaurantes e quais culinárias que são mais exploradas. Além disso, tem que fornecer o preço médio das refeições, a classificação dos restaurantes e a média de avaliação.

Para este desafio, foram passados 5 arquivos json contendo informações sobre restaurantes e 1 planilha de países. Inicialmente os arquivos json foram combinados pra gerar apenas uma única tabela de restaurantes. Em seguida, normalizei esta tabela gerando outras a partir de algumas colunas. Foram geradas as tabelas tipos de culinária, localização e user rating. Por último, foi importada uma api para efetuar a conversão da moeda local da Índia para o real brasileiro.

Visualize o dashboard em <a href="https://app.powerbi.com/view?r=eyJrIjoiYjk3Yzc0ZTUtMjRiOC00MGFkLWExNWEtMzI4OWE0Njc2MTkxIiwidCI6IjRlOWJkOTMzLTAyOTgtNDdlOC05MDhkLTVlYTI1MTVlNWY1MiJ9&pageName=ReportSection3f18dc50713276169ec0">Dashboard Alura Food - Semana 2</a>

A terceira empresa, Alura Skimo, necessita acompanhar suas vendas através de um painel que comporte todas métricas necessárias. A análise precisa identificar o faturamento, custo e lucro da empresa. Além disso, é preciso saber a quantidade de vendas e quais são os produtos e categorias de produtos mais vendidos. E por último, quais vendedores geram maior faturamento.

Neste desafio foi utilizado um backup de uma base de dados MYSQL. Após a restauração do backup foi preciso criar os relacionamentos entre as tabelas e tratar algumas linhas inconsistentes.

<a href="https://app.powerbi.com/view?r=eyJrIjoiZWVkNjEzMzMtODUzOC00NGRkLTlhOWQtZmRjODkxMjA0ZDBmIiwidCI6IjRlOWJkOTMzLTAyOTgtNDdlOC05MDhkLTVlYTI1MTVlNWY1MiJ9">Dashboard Alura Skimo - Semana 3</a>

