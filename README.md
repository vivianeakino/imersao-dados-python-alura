Dashboard de Salários na Área de Dados

Este projeto consiste em um dashboard interativo desenvolvido com Streamlit para análise de salários na área de dados, permitindo explorar informações por ano, senioridade, tipo de contrato, tamanho da empresa, regime de trabalho e país. O objetivo é facilitar a análise exploratória de dados salariais e apoiar estudos sobre o mercado de trabalho em Data Science.

Funcionalidades:
Filtros interativos na barra lateral e visualizações interativas

Tecnologias Utilizadas:

Python;
Streamlit;
Pandas;
Plotly Express;


Fonte dos Dados:
Os dados são carregados diretamente de um arquivo CSV hospedado no GitHub:
https://raw.githubusercontent.com/vqrca/dashboard_salarios_dados/refs/heads/main/dados-imersao-final.csv
O dataset contém informações sobre salários na área de dados, incluindo cargo, senioridade, tipo de contrato, regime de trabalho, país e ano.

Como Executar o Projeto:
Clone o repositório
git clone https://github.com/vqrca/dashboard_salarios_dados.git
cd dashboard_salarios_dados

Crie um ambiente virtual (opcional, mas recomendado):
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows

Instale as dependências:
pip install streamlit pandas plotly

Execute o aplicativo:
streamlit run app.py


Visualização interativa

Construção de dashboards com Streamlit

Comunicação de insights a partir de dados
