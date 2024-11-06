# 🎬 IMDb Scraper - A Jornada pelo Mundo dos Filmes 🎥

Bem-vindo ao **IMDb Scraper**, o projeto que leva você para uma viagem pelos filmes mais populares do **IMDb**! Este script foi criado para realizar um **web scraping** na página de filmes mais populares, extraindo informações valiosas sobre os filmes em alta. É um projeto para quem quer aprender mais sobre **requisições HTTP**, **análise de HTML** e **manipulação de dados** usando **Python**.

Prepare a pipoca, ajuste o assento e vamos começar!

## 🍿 Funcionalidades

Este projeto possui as seguintes funcionalidades, essenciais para quem quer fazer uma imersão no universo cinematográfico:

- 🎥 Realiza **requisições HTTP** à página de filmes populares do IMDb.
- 🏆 Extrai informações detalhadas sobre cada filme, incluindo:
  - **Título**: O nome da estrela principal.
  - **Data de Lançamento**: Quando o filme chegou às telas.
  - **Classificação**: Avaliação dos críticos e fãs.
  - **Sinopse**: Um resumo da trama.
- 📂 **Exporta os dados** extraídos para um arquivo CSV chamado `movies.csv`, perfeito para fazer a sua própria análise cinematográfica.
- ⚡ Utiliza **múltiplas threads** para acelerar o processo de coleta de dados, como se fosse uma superprodução de Hollywood.

## 💻 Tecnologias Utilizadas

Este projeto é feito com as melhores ferramentas do mundo da programação, como um filme de sucesso:

- **Python**: A linguagem que traz toda a magia por trás da cena.
- **Bibliotecas**:
  - `requests`: Para realizar requisições HTTP, como um diretor comandando a comunicação entre o servidor e o navegador.
  - `BeautifulSoup`: Para analisar o HTML e tirar o melhor proveito dos dados, como um crítico especializado desvendando os detalhes de um filme.
  - `concurrent.futures`: Para realizar tarefas simultâneas, como um elenco de estrelas trabalhando ao mesmo tempo para acelerar a produção.

## 🎬 Como Rodar o Projeto

1. Clone este repositório no seu computador:
   ```bash
   git clone https://github.com/lenonmerlo/01-imdb-scraper-exercicio.git

2. Instale as dependências necessárias:
  ```bash
  pip install -r requirements.txt

3. Execute o script:
  ```bash
  python imdb_scraper.py

4. Aguarde enquanto os dados são extraídos e o arquivo movies.csv é gerado.

### 🌟 Contribua para o Mundo do Cinema
Quer adicionar mais funcionalidades ao projeto? Imagine o que mais pode ser extraído do IMDb! Faça um fork do repositório, adicione suas contribuições e abra um pull request. Vamos continuar fazendo o IMDb Scraper um verdadeiro blockbuster!