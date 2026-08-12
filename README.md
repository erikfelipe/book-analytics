# 📚 Book Analytics

Análise exploratória dos meus hábitos de leitura utilizando Python, Pandas, 
Matplotlib e Power BI.

O projeto utiliza meu histórico pessoal de leitura para investigar padrões 
de volume, ritmo, preferências e avaliações ao longo do tempo.

## 🎯 Objetivos

- Analisar a evolução do volume de leitura ao longo dos anos
- Identificar gêneros, autores e séries mais frequentes
- Analisar o ritmo de leitura e sua evolução ao longo do tempo
- Investigar a relação entre características dos livros e o ritmo de leitura
- Investigar fatores associados às avaliações atribuídas aos livros
- Construir um dashboard interativo com os principais indicadores

## 🗂️ Dados

O dataset contém informações sobre os livros lidos, incluindo:

- Título
- Autor
- Número de páginas
- Ano de publicação
- Gênero e subgênero
- Formato (físico ou ebook)
- Avaliação
- Data de início e término da leitura
- Informações sobre séries
- Informações de aquisição

Atualmente, o conjunto de dados contém **54 livros concluídos**.

## 🔎 Análises

O projeto está organizado nas seguintes etapas:

### Evolução dos hábitos de leitura
- Quantidade de livros concluídos por ano
- Quantidade de páginas lidas por ano
- Evolução do ritmo de leitura
- Distribuição das leituras ao longo dos meses

### Perfil de leitura
- Distribuição por gênero
- Ficção vs. Não Ficção
- Autores mais lidos
- Séries mais lidas
- Distribuição por formato
- Distribuição pelo país do autor
- Ano de publicação

### Ritmo de leitura
- Tempo necessário para concluir os livros
- Relação entre tamanho do livro e tempo de leitura
- Relação entre tamanho do livro e páginas lidas por dia
- Diferenças de ritmo entre gêneros
- Físico vs. ebook

### Avaliações
- Avaliação média por gênero
- Relação entre tamanho do livro e avaliação
- Físico vs. ebook

## 📊 Dashboard

Dashboard desenvolvido em Power BI com os principais indicadores e 
visualizações obtidos durante a análise.

*Em desenvolvimento.*

## 📓 Análise completa

A análise exploratória, tratamento dos dados e desenvolvimento das métricas 
estão disponíveis no notebook:

[Notebook de análise](./notebooks/book_analytics.ipynb)

## 🛠️ Tecnologias

- Python
- Pandas
- Matplotlib
- Power BI

## 📁 Estrutura do projeto

```text
book-analytics/
│
├── data/
│   └── livros.csv
│
├── notebooks/
│   └── book_analytics.ipynb
│
├── dashboard/
│   └── ...
│
└── README.md
