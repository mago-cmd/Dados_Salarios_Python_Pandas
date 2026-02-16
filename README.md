# 📊 Dashboard de Salários na Área de Dados

Este projeto foi desenvolvido durante a **Imersão de Dados da Alura** utilizando **Python**, **Streamlit**, **Pandas** e **Plotly Express**.  
O objetivo é criar um **dashboard interativo** que permita explorar e analisar dados salariais na área de dados, considerando diferentes variáveis como ano, senioridade, tipo de contrato, tamanho da empresa e país de residência.

---

## 🚀 Funcionalidades

- **Filtros interativos** na barra lateral:
  - Ano
  - Senioridade
  - Tipo de contrato
  - Tamanho da empresa

- **Métricas principais (KPIs):**
  - Salário médio anual (USD)
  - Salário máximo anual (USD)
  - Total de registros filtrados
  - Cargo mais frequente

- **Visualizações dinâmicas com Plotly:**
  - Top 10 cargos por salário médio
  - Distribuição de salários anuais
  - Proporção dos tipos de trabalho (remoto/presencial/híbrido)
  - Salário médio de Cientistas de Dados por país (mapa interativo)

- **Tabela detalhada** com os dados filtrados.

---

## 🛠️ Tecnologias Utilizadas

- [Python](https://www.python.org/)
- [Streamlit](https://streamlit.io/) → para criação da interface interativa
- [Pandas](https://pandas.pydata.org/) → para manipulação e análise dos dados
- [Plotly Express](https://plotly.com/python/plotly-express/) → para visualizações gráficas

---

## 📂 Estrutura do Projeto
```
dashboard-salarios-dados/
│
├── app.py                # Código principal do dashboard
├── dados-imersao-final.csv  # Base de dados utilizada (link remoto)
└── README.md             # Documentação do projeto

```

---

## ▶️ Como Executar

- Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/dashboard-salarios-dados.git
   
- Instale as dependências:

pip install streamlit pandas plotly

- Execute o projeto:

streamlit run app.py

Abra o navegador no endereço indicado pelo Streamlit (geralmente http://localhost:8501

## 📈 Exemplos de Uso
- Descobrir quais cargos possuem os maiores salários médios.

- Visualizar a distribuição de salários por faixa.

- Comparar salários de Cientistas de Dados em diferentes países.

- Analisar como o tipo de contrato e o tamanho da empresa influenciam na remuneração.

## 📈 Aprendizados
- Manipulação de dados com Pandas (filtros, agrupamentos, estatísticas).

- Criação de dashboards interativos com Streamlit.

- Uso de gráficos avançados com Plotly.

- Estruturação de um projeto simples e funcional em Python.

