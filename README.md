# Classificação do Brasileirão - Web Scraping com Pandas

Este projeto em Python realiza a extração da tabela de classificação da Série A do Campeonato Brasileiro diretamente do site da ESPN Brasil e organiza os dados em um DataFrame limpo e estruturado.

---

## Funcionalidades

- Web scraping da classificação da Série A (Brasileirão) via ESPN Brasil.
- Tratamento de dados:
  - Limpeza dos nomes dos clubes (remoção de iniciais e números).
  - Junção da tabela de nomes dos times com a tabela de pontos e estatísticas.
- Visualização pronta para exportação ou uso em dashboards.

---

## Requisitos

- Python 3.7+
- Bibliotecas necessárias:
  - `pandas`
  - `requests`
  - `re` (regex)
  - `plotly` (opcional, para gráficos adicionais)

Instale as dependências com:

```bash
pip install pandas requests plotly
