# 📊 Dashboard de Análise de Salários na Área de Dados

Este projeto é um **dashboard interativo** desenvolvido com **Streamlit**, **Pandas** e **Plotly**, focado na análise de salários na área de dados ao longo dos anos.

O objetivo é permitir a exploração visual e filtrada dos dados salariais de forma simples, clara e interativa.

---

## 🚀 Funcionalidades

- Filtros interativos por:
  - Ano
  - Nível de experiência
  - Tipo de contrato
  - Tamanho da empresa

- Métricas principais (KPIs):
  - Salário médio anual (USD)
  - Salário máximo
  - Total de registros
  - Cargo mais frequente

- Visualizações:
  - Top 10 cargos por salário médio
  - Distribuição de salários
  - Proporção entre tipos de trabalho (remoto, híbrido e presencial)
  - Mapa mundial com salário médio de **Data Scientists** por país

- Tabela interativa com os dados filtrados

---

## 🧠 Tecnologias Utilizadas

- **Python**
- **Streamlit**
- **Pandas**
- **Plotly Express**

---

## 📁 Estrutura do Projeto

- 📦 projeto  
  - 📜 app.py  
  - 📄 salarios_limpos.csv  
  - 📘 README.md  

---

## ▶️ Como Executar o Projeto

### 1. Clone o repositório
```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
```

### 2. Instale as dependências
```bash
pip install streamlit pandas plotly
```

### 3. Execute a aplicação
```bash
streamlit run app.py
```

### 4. Acesse no navegador
```bash
http://localhost:8501
```

---

## 📊 Fonte dos Dados

O arquivo `salarios_limpos.csv` contém dados tratados com as seguintes informações:

- Cargo
- Salário anual em USD
- Ano
- Experiência
- Tipo de contrato
- Tipo de trabalho (remoto/presencial)
- País de residência

---

## 📌 Observações

- Todos os valores salariais estão em **USD (anual)**  
- Gráficos e métricas se atualizam automaticamente conforme os filtros  
- Quando não há dados disponíveis, o dashboard exibe mensagens de aviso
