# IMDb Scraper

Este projeto tem como objetivo realizar um web scraping na página de filmes mais populares do IMDb. O código foi desenvolvido para fins de estudo e aprendizado sobre requisições HTTP, análise de HTML e manipulação de dados com Python.

## Funcionalidades

- Realiza requisições à página de filmes populares do IMDb.
- Extrai informações detalhadas sobre cada filme, incluindo:
  - Título
  - Data de lançamento
  - Classificação
  - Sinopse
- Exporta os dados extraídos para um arquivo CSV chamado `movies.csv`.
- Utiliza múltiplas threads para acelerar o processo de extração de dados.

## Tecnologias Utilizadas

- Python
- Bibliotecas:
  - `requests`: Para realizar requisições HTTP.
  - `BeautifulSoup`: Para a análise de HTML.
  - `concurrent.futures`: Para execução de tarefas simultâneas.