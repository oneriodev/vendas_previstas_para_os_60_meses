# vendas_previstas_para_os_60_meses
Este projeto utiliza regressão linear para prever vendas futuras com base em dados históricos, explorando variáveis como tempo, número de clientes e ticket médio, além de avaliar a precisão do modelo com métricas e gráficos que facilitam a interpretação dos resultados.

# Previsão de Vendas com Regressão Linear

Este projeto utiliza técnicas de Machine Learning para prever vendas futuras com base em dados históricos, considerando variáveis como número de clientes, ticket médio, dia da semana e tempo.

## Funcionalidades

- Carregamento e pré-processamento dos dados (tratamento de datas, conversão de valores);
- Análise exploratória com gráficos para entender tendências e correlações;
- Treinamento de modelo de regressão linear para previsão de vendas;
- Avaliação do modelo com métricas como MAE, RMSE, R² e MAPE;
- Geração de previsões para os próximos 60 dias;
- Visualização das previsões comparadas aos dados reais.

## Como usar

1. Faça o upload do arquivo `vendas.csv` com os dados históricos no formato esperado.
2. Execute o script para pré-processar os dados, treinar o modelo e gerar previsões.
3. Analise os gráficos gerados para entender a performance e as tendências.

## Requisitos

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
