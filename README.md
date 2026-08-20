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

## Metodologia

- Tratamento e padronização dos dados utilizando Pandas
- Criação de métricas relacionadas a duração da leitura, páginas/dia e avaliações
- Análise exploratória utilizando Python e Matplotlib
- Construção do modelo analítico e dashboard no Power BI
- Utilização de medidas DAX para os principais indicadores

## 💡 Principais Insights

### Crescimento do ritmo de leitura
<img width="842" height="470" alt="image" src="https://github.com/user-attachments/assets/90d55810-7546-4d2b-991a-aafbe61de132" />

A velocidade média de leitura apresentou queda entre 2020 e 2022, seguida de uma recuperação a partir de 2024. O maior aumento ocorreu em 2025, quando a média passou de 38,4 para 68,1 páginas por dia. Em 2026, o ritmo permaneceu elevado, com média de 62,8 páginas por dia. A mediana apresenta comportamento semelhante, reforçando que o aumento observado nos anos mais recentes não está concentrado apenas em alguns livros.

### Diferenças de ritmo entre formatos
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

Acessar dashboard interativo
https://app.powerbi.com/view?r=eyJrIjoiMDgyYzBjZmQtMTQ3YS00YWU3LWExMmMtMTc1ZTI3NmNmODBhIiwidCI6IjY1OWNlMmI4LTA3MTQtNDE5OC04YzM4LWRjOWI2MGFhYmI1NyJ9

<img width="1111" height="625" alt="image" src="https://github.com/user-attachments/assets/af7d043e-eac7-4f40-aeb2-54130fe68820" />

Dashboard interativo desenvolvido em Power BI a partir das métricas e análises realizadas no notebook.

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
│   └── book_analytics.pbix
│
└── README.md
