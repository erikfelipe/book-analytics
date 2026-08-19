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

### Crescimento do ritmo de leitura
<img width="842" height="470" alt="image" src="https://github.com/user-attachments/assets/90d55810-7546-4d2b-991a-aafbe61de132" />

A quantidade de livros concluídos varia consideravelmente ao longo dos meses. Abril apresentou o maior volume de leituras, com 9 livros concluídos, seguido por dezembro, com 8. Novembro apresentou o menor volume, com apenas 1 livro. Apesar das diferenças observadas, não é possível identificar um padrão sazonal claro apenas com os dados disponíveis.

### O formato influencia o ritmo
<img width="842" height="470" alt="image" src="https://github.com/user-attachments/assets/24bf0161-d01c-4b84-9c96-5bff031e2994" />

Na amostra analisada, o formato digital apresentou uma velocidade de leitura significativamente maior que o formato físico. Entretanto, a diferença deve ser interpretada como uma associação observada nos dados, já que outros fatores podem influenciar o ritmo de leitura.

### Avaliações
<img width="833" height="592" alt="image" src="https://github.com/user-attachments/assets/7c153f06-2e7f-4dc9-95da-58e7ffc4288f" />

A avaliação média dos livros foi de 3,98/5. Entre os gêneros com maior quantidade de livros, Fantasia apresentou a maior avaliação média (4,25), seguida por Ficção Científica (4,18) e Suspense (4,11). Terror apresentou a menor média entre esses gêneros, com 3,17.

Os gêneros com poucos registros devem ser interpretados com cautela, pois uma quantidade reduzida de livros não é suficiente para representar uma preferência consolidada.

### Queda nas avaliações recentes
<img width="833" height="471" alt="image" src="https://github.com/user-attachments/assets/6ab8383a-f8e1-4862-9476-c3ab9c0144a0" />

As avaliações apresentam pouca relação com características físicas dos livros, como tamanho e formato, sendo mais influenciadas pelo gênero e pelo período de leitura. Embora a mudança no perfil dos gêneros tenha contribuído para a queda das avaliações em 2025, a redução observada em 2026 permanece mesmo após considerar essa mudança, indicando uma alteração mais recente no padrão de avaliação.

## 📊 Dashboard

Dashboard desenvolvido em Power BI com os principais indicadores e visualizações obtidos durante a análise.

*Em desenvolvimento.*

## 📓 Análise completa

A análise exploratória, tratamento dos dados e desenvolvimento das métricas estão disponíveis no notebook:

[Notebook de análise](https://github.com/erikfelipe/book-analytics/blob/main/notebooks/book_analytics.ipynb)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erikfelipe/book-analytics/blob/main/book-analytics.ipynb)

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
