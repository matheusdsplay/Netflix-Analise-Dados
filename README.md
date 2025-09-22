# Análise Exploratória de Dados Netflix

Este projeto contém uma série de análises e visualizações de dados sobre títulos da Netflix, utilizando o dataset netflix_titles.csv. O objetivo é extrair informações e tendências sobre o catálogo da plataforma.

# Arquivos do Projeto

limpeza-dados.ipynb: Este notebook realiza a limpeza inicial do conjunto de dados. Ele remove linhas duplicadas e trata valores ausentes nas colunas principais (director, cast, country, date_added), salvando o resultado em um novo arquivo CSV netflix_titles_limpo.csv.

quantidade-país.ipynb: Analisa a distribuição de títulos por país e gera um gráfico de barras com os 10 países que mais produziram conteúdo. Assegura que os nomes de países sejam exibidos em português.

lancamento-por-ano.ipynb: Este notebook explora o número de lançamentos de filmes e séries entre os anos de 2012 e 2025, criando um gráfico de linha para mostrar a tendência ao longo do tempo.

categorias-lancamento.ipynb: Identifica as categorias mais frequentes e gera um gráfico de barras horizontais com as 10 categorias com maior número de lançamentos entre 2012 e 2025.

series-filmes.ipynb: Faz uma análise da distribuição de tipos de conteúdo (série ou filme). Também identifica e conta as 10 categorias mais populares de lançamentos no período de 2012 a 2025.

# Tecnologias e Dependências

Python: Linguagem de programação. 
Pandas: Biblioteca para manipulação e análise de dados. 
Matplotlib: Biblioteca para visualização de dados. 
Jupyter Notebook: Ambiente interativo para rodar os notebooks.
