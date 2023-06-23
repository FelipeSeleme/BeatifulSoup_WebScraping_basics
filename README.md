# Web Scraping com BeautifulSoup
Essa é uma aplicação simples de web scraping utilizando a biblioteca BeautifulSoup do Python.  
O objetivo é extrair informações de um site e formatar os dados para serem exportados em JSON, prontos para serem consumidos por uma API.  

## Introdução
O web scraping é uma técnica de extração de dados de sites.
Para isso, é necessário analisar a estrutura do site e identificar os elementos que contém as informações desejadas.  
Com essas informações, é possível criar um script que acesse o site e extraia os dados desejados.  
Usando a biblioteca BeautifulSoup, é possível formatar os dados extraídos em um arquivo JSON, que pode ser consumido por uma API. 
   
Como exemplo, usaremos o site [CoinMarketCap](https://coinmarketcap.com/), que contém informações sobre criptomoedas.  
Ao fim do projeto, teremos extraído as informações das criptomoedas e formatado em um dicionário JSON.

## Índice
- [basics.ipynb](#basics.ipynb) - Introdução ao BeautifulSoup
- [coinmarketWS.ipynb](#coinmarketWS.ipynb) - Web Scraping do site CoinMarketCap