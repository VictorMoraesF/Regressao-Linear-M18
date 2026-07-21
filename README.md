🏠 Projeto de Regressão Linear para Previsão de Aluguel de Imóveis
📌 Descrição

Este projeto tem como objetivo aplicar técnicas de Análise Exploratória de Dados (EDA) e Machine Learning para prever o valor de aluguel de imóveis utilizando modelos de Regressão Linear Simples e Regressão Linear Múltipla.

Durante o desenvolvimento foram realizadas etapas de exploração dos dados, identificação de valores nulos e outliers, análise bivariada e construção de modelos preditivos utilizando a biblioteca Scikit-Learn.

🎯 Objetivos
Explorar o conjunto de dados de imóveis para aluguel.
Identificar inconsistências nos dados (valores nulos e outliers).
Realizar análises gráficas para compreender a relação entre as variáveis.
Construir um modelo de Regressão Linear Simples utilizando apenas a variável Metragem.
Construir um modelo de Regressão Linear Múltipla utilizando todas as variáveis explicativas.
Comparar o desempenho dos modelos utilizando o coeficiente de determinação (R²).
📊 Base de Dados

O conjunto de dados contém informações sobre imóveis disponíveis para aluguel, incluindo características como:

Metragem
Número de Quartos
Número de Banheiros
Número de Suítes
Número de Vagas
Valor do Condomínio
Valor do Aluguel (variável alvo)
🛠 Tecnologias Utilizadas
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-Learn
Jupyter Notebook
📈 Etapas do Projeto
1. Importação das Bibliotecas

Foram importadas as bibliotecas necessárias para manipulação dos dados, visualização gráfica e criação dos modelos de Machine Learning.

2. Análise Exploratória dos Dados (EDA)

Nesta etapa foram realizadas:

Visualização das primeiras linhas do DataFrame.
Verificação dos tipos de dados.
Estatísticas descritivas.
Identificação de valores nulos.
Identificação de possíveis outliers.
3. Análise Bivariada

Foram construídos gráficos para avaliar a relação entre o valor do aluguel e outras variáveis do conjunto de dados.

Gráficos utilizados:

Metragem × Valor do Aluguel
Número de Quartos × Valor do Aluguel
Valor do Condomínio × Valor do Aluguel
Boxplot do Valor do Aluguel
Principais Insights
Imóveis com maior metragem tendem a apresentar aluguéis mais elevados.
O número de quartos possui relação positiva com o valor do aluguel.
O valor do condomínio apresenta associação com imóveis de maior padrão.
Foram identificados outliers representando imóveis de alto padrão, com valores de aluguel significativamente superiores aos demais.
🤖 Regressão Linear Simples

Foi desenvolvido um modelo utilizando apenas a variável Metragem para prever o valor do aluguel.

Etapas
Separação entre treino e teste.
Treinamento do modelo.
Realização das previsões.
Avaliação utilizando o coeficiente R².
Objetivo

Avaliar quanto da variação do valor do aluguel pode ser explicada apenas pela metragem do imóvel.

🤖 Regressão Linear Múltipla

Posteriormente foi desenvolvido um modelo considerando todas as variáveis explicativas disponíveis.

Variáveis utilizadas:

Metragem
Número de Quartos
Número de Banheiros
Número de Suítes
Número de Vagas
Valor do Condomínio
Etapas
Separação entre treino e teste.
Treinamento do modelo.
Predições na base de teste.
Avaliação utilizando R².

📌 Comparação entre os Modelos

A Regressão Linear Múltipla apresentou desempenho superior ao modelo de Regressão Linear Simples.

Isso ocorreu porque o valor do aluguel depende de diversos fatores além da metragem, como quantidade de quartos, banheiros, vagas de garagem, suítes e valor do condomínio.

Ao considerar todas essas características, o modelo consegue representar melhor a realidade do mercado imobiliário, reduzindo o erro das previsões.

📊 Conclusão

O projeto demonstrou a importância da Análise Exploratória de Dados antes da construção de modelos de Machine Learning.

Foi possível identificar padrões, relações entre variáveis e compreender como diferentes características dos imóveis influenciam diretamente o valor do aluguel.

A comparação entre os modelos mostrou que a Regressão Linear Múltipla apresentou melhor desempenho, explicando uma parcela maior da variação do preço dos imóveis quando comparada à Regressão Linear Simples.

Além disso, a proximidade entre os valores de R² obtidos nas bases de treino e teste indica que o modelo possui boa capacidade de generalização, sendo capaz de realizar previsões consistentes para novos dados.

👨‍💻 Autor

Victor Moraes

Projeto desenvolvido como prática de Análise de Dados e Machine Learning, aplicando técnicas de regressão linear para previsão de preços de aluguel de imóveis utilizando Python e Scikit-Learn.
