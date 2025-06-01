- Análise de Dados COVID-19 no Brasil

    Este projeto tem como objetivo explorar, analisar e modelar os dados da pandemia de COVID-19 com foco no Brasil. 
    Através da aplicação de técnicas estatísticas e de aprendizado de máquina, buscamos entender a distribuição dos casos e mortes,
    além de prever comportamentos futuros com base em regressão.

-  Objetivos do Projeto
    Importar e limpar os dados da COVID-19.
    Explorar visualmente os dados para identificar padrões e tendências.
    Avaliar a normalidade das variáveis.
    Aplicar regressão linear simples e polinomial para modelar a evolução dos casos.
    Avaliar o desempenho dos modelos com métricas como R², MAE e RMSE.

- Estrutura do Projeto
    Importação de bibliotecas:
        pandas, numpy, matplotlib, seaborn, plotly, scipy, sklearn
    Leitura dos dados: 
        Arquivo CSV com dados globais da COVID-19.
    Filtragem: 
        Seleção dos dados apenas do Brasil.
    Análise Exploratória:
        Visualização de histogramas e gráficos de dispersão.
        Análise de normalidade com teste de Shapiro-Wilk.
    Modelagem Preditiva:
        Regressão linear simples com LinearRegression.
        Testes com regressão polinomial para melhor ajuste dos dados.
    Métricas Avaliadas:
        R² (coeficiente de determinação)
        MAE (erro absoluto médio)
        RMSE (raiz do erro quadrático médio)

 - Exemplos de Visualizações

    Histogramas de casos e mortes (novos e acumulados)
    Gráficos de dispersão com plotly mostrando a evolução temporal
    Gráficos de probabilidade normal (QQ plots)

- Requisitos

    Python 3.x
    Pandas
    Numpy
    Seaborn
    Plotly
    Scikit-learn
    Scipy
    Matplotlib

- Conclusões
    Os dados de casos e mortes apresentam crescimento exponencial em certos períodos.
    As distribuições não seguem uma normalidade clara (conforme teste de Shapiro).
    Modelos de regressão polinomial apresentaram melhor ajuste (R² ~77%) em comparação com a regressão linear simples.