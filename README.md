# Web Scrapper Learning Project

Projeto desenvolvido como estudo e teste de um modelo de Web Scrapper utilizando Python.

O objetivo deste projeto foi praticar conceitos de coleta de dados na web, leitura de páginas HTML, extração de informações específicas e armazenamento dos dados coletados em um arquivo CSV.

Este projeto tem foco educacional e foi criado para entender o funcionamento básico de um web scraper.

---

## Tecnologias utilizadas

- Python
- Jupyter Notebook
- BeautifulSoup
- Requests
- Pandas
- CSV

---

## Funcionalidades

- Acesso a páginas web usando Python
- Leitura do conteúdo HTML da página
- Extração de dados com BeautifulSoup
- Organização dos dados coletados
- Conversão dos dados para formato tabular
- Exportação dos dados para arquivo `.csv`
- Geração do arquivo `books.csv`
- Teste prático de um fluxo básico de Web Scraping

---

## Estrutura principal do projeto

```txt
webscrapper/
├── web_scraping_bs.ipynb
├── books.csv
└── README
```

---

## Objetivo do projeto

Este projeto foi criado com o objetivo de estudar como funciona um web scraper simples.

Durante o desenvolvimento, foram praticados conceitos como:

- Requisições HTTP
- Leitura de HTML
- Busca de elementos dentro da página
- Extração de textos e atributos
- Organização de dados em listas e tabelas
- Exportação dos dados para CSV
- Uso de notebooks para testes e aprendizado

---

## Como funciona

O fluxo principal do projeto é:

1. O notebook acessa uma página web.
2. O conteúdo HTML da página é carregado.
3. O BeautifulSoup interpreta a estrutura HTML.
4. O código procura os elementos desejados.
5. Os dados encontrados são extraídos.
6. As informações são organizadas em uma tabela.
7. O resultado final é salvo no arquivo `books.csv`.

---

## Arquivos do projeto

### web_scraping_bs.ipynb

Notebook principal do projeto.

Contém o código usado para testar e executar o web scraping.

Nele estão as etapas de:

- Importação das bibliotecas
- Requisição da página
- Leitura do HTML
- Extração dos dados
- Organização das informações
- Criação do arquivo CSV

---

### books.csv

Arquivo gerado a partir dos dados coletados pelo scraper.

Esse arquivo armazena as informações extraídas em formato tabular, podendo ser aberto em ferramentas como:

- Excel
- Google Sheets
- LibreOffice Calc
- Pandas
- VS Code

---

## Pré-requisitos

Antes de rodar o projeto, instale:

- Python 3
- pip
- Jupyter Notebook ou Jupyter Lab

Verifique se o Python está instalado:

```bash
python --version
```

ou:

```bash
python3 --version
```

Verifique se o pip está instalado:

```bash
pip --version
```

---

## Instalação

Clone o repositório:

```bash
git clone https://github.com/sixthy/webscrapper.git
```

Entre na pasta do projeto:

```bash
cd webscrapper
```

Crie um ambiente virtual:

```bash
python -m venv .venv
```

Ative o ambiente virtual no Windows:

```bash
.venv\Scripts\activate
```

Ative o ambiente virtual no Linux/Mac:

```bash
source .venv/bin/activate
```

Instale as dependências necessárias:

```bash
pip install requests beautifulsoup4 pandas notebook
```

---

## Rodando o projeto

Abra o Jupyter Notebook:

```bash
jupyter notebook
```

Depois, abra o arquivo:

```txt
web_scraping_bs.ipynb
```

Execute as células do notebook em ordem.

Ao final da execução, o arquivo `books.csv` será gerado ou atualizado com os dados coletados.

---

## Exemplo de bibliotecas usadas

```python
import requests
from bs4 import BeautifulSoup
import pandas as pd
```

---

## Saída esperada

Após executar o notebook, o projeto deve gerar um arquivo CSV com os dados extraídos.

Exemplo:

```txt
books.csv
```

Esse arquivo pode conter informações como:

- Nome do item
- Preço
- Disponibilidade
- Avaliação
- Link ou categoria, dependendo da estrutura usada no scraping

---

## Limitações do projeto

Como este projeto foi criado para estudo, ele pode ter algumas limitações...
Foi desenvolvido principalmente para entender o fluxo básico de scraping...


---

## Status 

Projeto de um estudo inicial de Web Scraping.

