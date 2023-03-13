# Regressão Linear - Previsão do plano de saúde com sklearn
Este é um projeto de regressão linear para prever o custo do plano de saúde de um paciente com base em suas características, como idade, sexo, índice de massa corporal, número de filhos e tabagismo. Usamos a biblioteca scikit-learn (sklearn) em Python para construir o modelo.

Para começar, importamos o conjunto de dados de pacientes que contém essas informações e seus respectivos custos com planos de saúde. Em seguida, fizemos uma análise exploratória dos dados para entender melhor as relações entre as variáveis e identificar possíveis outliers.

Depois, dividimos os dados em conjuntos de treinamento e teste e usamos a classe LinearRegression da sklearn para criar o modelo de regressão linear. Treinamos o modelo com o conjunto de treinamento e o validamos com o conjunto de teste. Ajustamos o modelo conforme necessário para obter uma boa precisão e evitar overfitting.

Por fim, avaliamos o modelo usando métricas como R² e RMSE para medir sua precisão. Usamos o modelo para prever o custo do plano de saúde de novos pacientes com base em suas características.

Criamos um repositório no GitHub para hospedar nosso código. O repositório inclui o código do modelo, o conjunto de dados de pacientes, os arquivos de conjunto de dados de treinamento e teste e o código para executar o modelo. Também documentamos o código com comentários e instruções claras para que outros possam entender e usar o modelo.

Com este projeto, esperamos fornecer uma ferramenta útil para previsão do custo do plano de saúde e incentivar outros desenvolvedores a contribuir para a melhoria do modelo.
