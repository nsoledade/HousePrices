** [Etapa 1: Modelo Inicial](https://github.com/nsoledade/HousePrices/blob/main/Etapa1.ipynb)
- A avaliação dos erros foi realizada usando-se o Erro Absoluto e o Erro Quadrático Médio.
- Etapa 1 visa criar um modelo inicial, avaliar o erro e nas etapas seguintes aperfeiçoar o modelo.
- Na Etapa 1 são eliminadas as colunas com mais de 90% de valores vazios. Os valores vazios restantes são substituídos por (-1).
- Após seleciona-se apenas as colunas numéricas.
- Os procedimentos acima são realizados para as bases treino e teste.
- A Regressão Linear apresentou o menor Erro Quadrático Médio: 0,25476.


**[Etapa 2: Abordagem dos valores vazios](https://github.com/nsoledade/HousePrices/blob/main/Etapa2.ipynb)
- Apurando a quantidadae de valores vazios.
- Verificando a correlaça7o entre  colunas.
- Verificando correlação entre colunas e preços.
- Escolha de indicadores estatísticos para substituir os valores vazios.
- Definindo um limita para tratamento de colunas. As demais colunas serão tratadas na Etapa 3.

** [Etapa 2: Modelos de Predição](https://github.com/nsoledade/HousePrices/blob/main/Etapa2Modelos.ipynb)
- Após o tratamento das colunas na Etapa 2, agora seliciona-se as colunas numéricas nas bases treino e teste.
- Os algoritmos utilizados são: Regressão Linear, Árvore de Regressão e KneighborsRegressor.
- A Regressão Linear apresentou o menor Erro Quadrático Médio: 0,18120.

