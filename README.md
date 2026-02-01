📊 Dashboard de Análise de Salários na Área de Dados

Este projeto é um dashboard interativo desenvolvido com Streamlit, Pandas e Plotly, focado na análise de salários na área de dados ao longo dos anos.
A ideia é simples: filtrar, visualizar e entender padrões salariais sem sofrer em planilhas infinitas.

🚀 Funcionalidades

Filtros interativos por:

Ano

Nível de experiência

Tipo de contrato

Tamanho da empresa

Métricas principais (KPIs):

Salário médio anual (USD)

Salário máximo

Total de registros

Cargo mais frequente

Visualizações:

Top 10 cargos com maior salário médio

Distribuição de salários

Proporção entre trabalho remoto, híbrido e presencial

Mapa mundial com salário médio de Data Scientists por país

Tabela interativa com os dados filtrados

🧠 Tecnologias Utilizadas

Python

Streamlit

Pandas

Plotly Express

📁 Estrutura do Projeto
.
├── app.py                  # Código principal do dashboard
├── salarios_limpos.csv     # Base de dados tratada
├── README.md               # Documentação do projeto

▶️ Como Executar o Projeto

Clone o repositório:

git clone https://github.com/seu-usuario/seu-repositorio.git


Instale as dependências:

pip install streamlit pandas plotly


Execute a aplicação:

streamlit run app.py


Abra o navegador no endereço exibido no terminal (geralmente http://localhost:8501).

📊 Fonte dos Dados

O arquivo salarios_limpos.csv contém dados salariais já tratados, incluindo informações como:

Cargo

Salário anual em USD

Ano

Experiência

Tipo de contrato

Trabalho remoto/presencial

País de residência

📌 Observações

Todos os valores salariais estão em USD (anual).

O dashboard se adapta automaticamente aos filtros selecionados.

Caso nenhum filtro retorne dados, os gráficos exibem mensagens de aviso.

🧑‍💻 Autor

Projeto desenvolvido para fins de estudo e análise de dados.
