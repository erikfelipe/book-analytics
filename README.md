# 📚 Book Analytics

Análise exploratória dos meus hábitos de leitura utilizando Python, Pandas, Matplotlib e Power BI.

O projeto utiliza meu histórico pessoal de leitura para investigar padrões de volume, ritmo, perfil de leitura e avaliações ao longo do tempo.

## 🎯 Objetivos

- Analisar a evolução do volume de leitura ao longo dos anos
- Identificar gêneros, autores e séries mais frequentes
- Analisar o ritmo de leitura e sua evolução ao longo do tempo
- Investigar a relação entre características dos livros e o ritmo de leitura
- Investigar fatores associados às avaliações atribuídas aos livros
- Identificar mudanças no perfil e no comportamento de leitura ao longo do tempo
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

### Evolução dos hábitos de leitura

- Quantidade de livros concluídos por ano
- Quantidade de páginas lidas por ano
- Evolução da velocidade de leitura
- Distribuição das leituras ao longo dos meses
- Comparação entre quantidade de livros e páginas lidas

### Perfil de leitura

- Distribuição por gênero
- Ficção vs. Não Ficção
- Autores mais lidos
- Séries mais lidas
- Distribuição por formato
- Distribuição pelo país do autor
- Distribuição por década de publicação

### Ritmo de leitura

- Tempo necessário para concluir os livros
- Relação entre tamanho do livro e tempo de leitura
- Relação entre tamanho do livro e páginas lidas por dia
- Diferenças de velocidade entre gêneros
- Diferenças de velocidade entre formatos

### Avaliações

- Avaliação média dos livros
- Avaliação média por gênero
- Relação entre tamanho do livro e avaliação
- Diferenças de avaliação entre formatos
- Evolução das avaliações ao longo dos anos
- Análise da influência da mudança no perfil de gêneros sobre as avaliações

## 💡 Principais Insights

- O volume e o ritmo de leitura apresentaram crescimento nos anos mais recentes, especialmente a partir de 2024.
- A mediana para concluir um livro foi de **8,5 dias**, enquanto a média foi de **22,2 dias**, indicando a influência de livros com períodos de leitura mais longos.
- O tamanho do livro apresentou pouca relação com o tempo necessário para sua conclusão, com correlação de **-0,07**.
- O formato digital apresentou velocidade de leitura superior ao formato físico, com medianas de **43,1 páginas/dia** e **14,5 páginas/dia**, respectivamente.
- As avaliações apresentaram média geral de **3,98/5**.
- Fantasia apresentou a maior avaliação média entre os gêneros com maior quantidade de registros, com **4,25/5**, enquanto Terror apresentou **3,17/5**.
- A avaliação média apresentou queda nos anos mais recentes, passando de **4,21 em 2024 para 3,69 em 2026**.
- A mudança no perfil dos gêneros contribuiu para a queda das avaliações em 2025, mas não explica a redução observada em 2026.

## 📊 Dashboard

Dashboard desenvolvido em Power BI com os principais indicadores e visualizações obtidos durante a análise.

*Em desenvolvimento.*

## 📓 Análise completa

A análise exploratória, tratamento dos dados e desenvolvimento das métricas estão disponíveis no notebook:

[Notebook de análise](https://github.com/erikfelipe/book-analytics/blob/main/notebooks/book_analytics.ipynb)

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
