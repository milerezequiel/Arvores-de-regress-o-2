# Árvore de Regressão com Poda (California Housing)

Este projeto faz parte de um exercício do curso de Ciência de Dados. O objetivo foi treinar árvores de regressão para prever o valor mediano de imóveis (`median_house_value`) utilizando a base de dados **California Housing**.

## Etapas realizadas

* Preparação e tratamento da base de dados
* Treinamento de uma árvore de regressão inicial
* Cálculo dos valores de poda utilizando `ccp_alpha`
* Treinamento de várias árvores com diferentes níveis de poda
* Avaliação dos modelos utilizando **MSE**
* Escolha do melhor valor de `alpha` com base no gráfico de erro
* Cálculo do **R²** do modelo escolhido
* Visualização da árvore final

## Conclusão

A análise permitiu identificar um valor de `ccp_alpha` que gera uma árvore com melhor equilíbrio entre complexidade e capacidade de generalização.

## Ferramentas utilizadas

* Python
* Pandas
* Matplotlib
* Scikit-learn
