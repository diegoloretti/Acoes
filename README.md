Análise de Ações com Streamlit

## Descrição
Este projeto implementa uma aplicação Streamlit para análise de ações financeiras. Utiliza a biblioteca `yfinance` para extrair dados do mercado de ações, `pandas` para manipulação de dados e `Prophet` para realizar previsões futuras. A aplicação permite aos usuários selecionar ações de um conjunto pré-definido, especificar a quantidade de dias para previsão e visualizar dados históricos e previsões futuras.

## Funcionalidades
- Escolha de ações financeiras através de uma interface interativa.
- Especificação do número de dias para previsão.
- Visualização de tabelas de valores recentes.
- Gráficos de preços históricos.
- Previsões de preços futuros com intervalos de confiança.

## Instalação
Para executar o projeto, é necessário instalar as seguintes bibliotecas:
```
pip install streamlit yfinance pandas prophet plotly
```

## Execução
Para iniciar a aplicação, execute o seguinte comando:
```
streamlit run main.py
```

## Bibliotecas Utilizadas
- `streamlit`: Criação de aplicações web interativas em Python.
- `yfinance`: Obtenção de dados históricos de ações.
- `pandas`: Manipulação e análise de dados.
- `Prophet`: Realização de previsões de séries temporais.
- `plotly`: Criação de gráficos interativos.
