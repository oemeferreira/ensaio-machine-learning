# Análise Comparativa de Algoritmos de Machine Learning

Este projeto consiste em uma análise detalhada e comparativa de algoritmos de Machine Learning, abrangendo as áreas de Classificação, Regressão e Clusterização. O objetivo principal é examinar a eficácia e eficiência desses algoritmos sob a ótica de métricas de desempenho estabelecidas, com ênfase especial no impacto dos ajustes de hiperparâmetros no controle de overfitting e underfitting. Utilizando conjuntos de dados padronizados, o estudo busca identificar as peculiaridades e potenciais de cada algoritmo, fornecendo insights valiosos sobre sua aplicabilidade em diferentes cenários de dados.

## Introdução

### Contexto sobre Machine Learning

A importância do Machine Learning reside na sua habilidade de processar grandes volumes de dados e extrair padrões e insights, o que é fundamental na era do Big Data. Esta característica torna-o indispensável para a tomada de decisões baseadas em dados, otimização de processos e inovação contínua. Além disso, a adaptabilidade dos algoritmos de Machine Learning a diferentes tipos de dados e contextos os torna ferramentas valiosas para uma ampla gama de aplicações práticas.

## Objetivos do Projeto

Este projeto visa realizar uma análise comparativa abrangente de algoritmos de Machine Learning, focando especificamente nas categorias de Classificação, Regressão e Clusterização. 

**O objetivo é duplo:** primeiro, proporcionar um entendimento profundo do comportamento e desempenho de cada algoritmo sob diferentes condições de dados, e segundo, explorar como ajustes em hiperparâmetros influenciam o equilíbrio entre overfitting e underfitting. Ao realizar esta análise, o projeto busca:

- Avaliar e comparar o desempenho dos algoritmos com base em métricas estabelecidas, aplicadas a conjuntos de dados de Treinamento, Validação e Teste.
- Identificar as melhores práticas para ajuste de hiperparâmetros em diferentes contextos de dados e algoritmos.
- Contribuir com insights práticos e teóricos para o campo do Machine Learning, auxiliando profissionais e acadêmicos na escolha e aplicação eficaz de algoritmos de Machine Learning.
- Fomentar uma compreensão mais profunda da aplicabilidade e limitações dos diversos algoritmos em cenários reais de dados.

Este estudo é projetado para ser um recurso valioso para pesquisadores, cientistas de dados e profissionais do setor, oferecendo uma análise comparativa detalhada que pode orientar a implementação eficaz de soluções de Machine Learning.

## Metodologia

### Descrição dos Algoritmos Utilizados

- **Algoritmos de Classificação:** Foram utilizados o K Nearest Neighbors (KNN), Decision Tree Classifier, Random Forest Classifier e Logistic Regression Classifier. Estes algoritmos foram escolhidos por representarem uma gama diversificada em termos de complexidade e abordagem, permitindo uma análise abrangente dos métodos de classificação.

- **Algoritmos de Regressão:** Incluíram-se modelos como Linear Regression, Decision Tree Regressor, Random Forest Regressor, Polinomial Regression, e suas variações regularizadas (Lasso, Ridge e Elastic Net). Essa seleção visa cobrir tanto modelos lineares simples quanto complexos, proporcionando uma visão ampla da regressão em Machine Learning.

- **Algoritmos de Clusterização:** Focou-se no K-Means e Affinity Propagation, escolhidos por suas características distintas em termos de abordagens de agrupamento, facilitando o estudo de técnicas de clusterização em diferentes cenários.

### Seleção de Conjuntos de Dados

Os conjuntos de dados foram selecionados com base em critérios de diversidade, representatividade e complexidade. Cada conjunto de dados foi utilizado para avaliar os algoritmos em três diferentes contextos: Treinamento, Validação e Teste. O objetivo foi garantir que os algoritmos fossem testados em condições variadas, proporcionando uma análise robusta e abrangente de seu desempenho.

- **Conjunto de Dados de Treinamento:** Utilizado para ajustar os modelos. A escolha visou dados representativos das condições reais de aplicação dos algoritmos.
- **Conjunto de Dados de Validação:** Empregado para o ajuste fino de hiperparâmetros, selecionado para avaliar a generalização dos modelos além do treinamento.
- **Conjunto de Dados de Teste:** Usado para avaliar o desempenho final dos modelos, escolhido para testar a eficácia dos algoritmos em condições inéditas.

### Ferramentas e Tecnologias Utilizadas

O projeto foi desenvolvido utilizando uma série de ferramentas e tecnologias de ponta no campo de Machine Learning e análise de dados:

- **Python (versão 3.10.9):** Linguagem de programação escolhida pela sua robustez, flexibilidade e ampla aceitação na comunidade de ciência de dados.
- **Jupyter Lab:** Utilizado para desenvolvimento interativo e documentação do processo de análise.
- **Scikit-learn (versão 1.2.1):** Biblioteca de Machine Learning em Python, escolhida pela sua vasta coleção de algoritmos e ferramentas para análise de dados.
- **Plotly (versão 5.9.0) e Seaborn (versão 0.12.2):** Ferramentas de visualização de dados para a criação de gráficos interativos e informativos.
- **NumPy (versão 1.23.5) e Pandas (versão 1.5.3):** Bibliotecas para manipulação e análise de dados em Python, essenciais para o tratamento dos conjuntos de dados.
- **Matplotlib (versão 3.7.0) e Yellowbrick (versão 1.5):** Utilizados para visualizações estáticas e diagnósticos de modelos.

Esta combinação de algoritmos, conjuntos de dados e ferramentas tecnológicas foi cuidadosamente selecionada para garantir uma análise rigorosa, relevante e atualizada das técnicas de Machine Learning.

## Desenvolvimento

### Análise dos Algoritmos de Classificação

Esta seção do projeto concentrou-se na análise detalhada de quatro algoritmos de classificação: KNN, Decision Tree Classifier, Random Forest Classifier e Logistic Regression Classifier. Cada algoritmo foi avaliado com base nas métricas de Accuracy, Precision, Recall e F1-Score. Abaixo estão os detalhes e as tabelas com as métricas de desempenho para cada algoritmo:

K Nearest Neighbors (KNN): Este algoritmo baseia-se na premissa de que dados semelhantes existem em proximidade. A análise focou em como a escolha do número de vizinhos ('K') afeta o desempenho do modelo.

Decision Tree Classifier: Estudou-se a eficácia deste modelo em criar estruturas de árvore baseadas em decisões lógicas. Aspectos como a profundidade da árvore e critérios de divisão foram analisados.

Random Forest Classifier: Como uma extensão do Decision Tree, este algoritmo usa múltiplas árvores para melhorar a precisão. A análise incluiu o número de árvores e a técnica de bagging.

Logistic Regression Classifier: Este modelo foi analisado por sua capacidade de classificar dados em categorias discretas, focando em aspectos como a regularização e a taxa de aprendizado.

#### Resultados de Treino para Classificação
| Modelo               | Accuracy | Precision | Recall   | F1-Score |
|----------------------|----------|-----------|----------|----------|
| KNN                  | 0.832186 | 0.831913  | 0.832186 | 0.831998 |
| Decision Tree        | 0.955444 | 0.955642  | 0.955444 | 0.955349 |
| Random Forest        | 1.000000 | 1.000000  | 1.000000 | 1.000000 |
| Logistic Regression  | 0.876081 | 0.875951  | 0.876081 | 0.875757 |

#### Resultados de Validação para Classificação
| Modelo               | Accuracy | Precision | Recall   | F1-Score |
|----------------------|----------|-----------|----------|----------|
| KNN                  | 0.676277 | 0.675892  | 0.676277 | 0.676070 |
| Decision Tree        | 0.947006 | 0.947177  | 0.947006 | 0.946891 |
| Random Forest        | 0.964864 | 0.965059  | 0.964864 | 0.964796 |
| Logistic Regression  | 0.874385 | 0.874241  | 0.874385 | 0.874061 |

#### Resultados de Teste para Classificação
| Modelo               | Accuracy | Precision | Recall   | F1-Score |
|----------------------|----------|-----------|----------|----------|
| KNN                  | 0.672228 | 0.671287  | 0.672228 | 0.671644 |
| Decision Tree        | 0.945931 | 0.946050  | 0.945931 | 0.945838 |
| Random Forest        | 0.964006 | 0.964173  | 0.964006 | 0.963946 |
| Logistic Regression  | 0.871510 | 0.871400  | 0.871510 | 0.871202 |


### Análise dos Algoritmos de Regressão

Avaliamos modelos de regressão, incluindo Linear Regression, Decision Tree Regressor, Random Forest Regressor, entre outros, usando as métricas MSE, RAMSE, MAE e MAPE:

Linear Regression e Variações (Lasso, Ridge, Elastic Net): Analisou-se a performance destes modelos em relação a diferentes graus de regularização e a influência dos hiperparâmetros na redução do overfitting.

Decision Tree Regressor: Investigou-se a capacidade do modelo de capturar padrões não lineares, avaliando a profundidade da árvore e os critérios de divisão.

Random Forest Regressor: Estudou-se a eficiência deste modelo em reduzir a variação sem aumentar o viés, através do número de árvores e do método de amostragem.

#### Resultados de Treino para Regressão
| Modelo                            | R2       | MSE        | RMSE      | MAE       | MAPE     |
|-----------------------------------|----------|------------|-----------|-----------|----------|
| Decision Tree                     | 0.384624 | 294.157341 | 17.151016 | 12.925051 | 4.871412 |
| Random Forest                     | 0.904832 |  45.491423 |  6.744733 |  4.823036 | 2.621872 |
| Logistic Regression               | 0.046058 | 455.996112 | 21.354065 | 16.998249 | 8.653186 |
| Logistic Regression Ridge         | 0.046045 | 456.002667 | 21.354219 | 16.998596 | 8.654275 |
| Logistic Regression Lasso         | 0.007401 | 474.474834 | 21.782443 | 17.305484 | 8.736697 |
| Logistic Regression Elastic Net   | 0.010715 | 472.890766 | 21.746052 | 17.277098 | 8.719880 |
| Polinomial Regression             | 0.094195 | 432.986210 | 20.808321 | 16.458032 | 8.350540 |
| Polinomial Regression Ridge       | 0.092544 | 433.775338 | 20.827274 | 16.479345 | 8.382553 |
| Polinomial Regression Lasso       | 0.009150 | 473.638776 | 21.763244 | 17.285450 | 8.699701 |
| Polinomial Regression Elastic Net | 0.026167 | 465.504391 | 21.575551 | 17.120834 | 8.637742 |
  
#### Resultados de Validação para Regressão
| Modelo                            | R2       | MSE        | RMSE      | MAE       | MAPE     |
|-----------------------------------|----------|------------|-----------|-----------|----------|
| Decision Tree                     | -0.010764| 482.651378 | 21.969328 | 16.907509 | 7.894565 |
| Random Forest                     |  0.336046| 317.045637 | 17.805775 | 12.990506 | 7.046859 |
| Logistic Regression               |  0.039925| 458.447042 | 21.411376 | 17.039754 | 8.682542 |
| Logistic Regression Ridge         |  0.039936| 458.441514 | 21.411247 | 17.038532 | 8.681918 |
| Logistic Regression Lasso         |  0.007884| 473.747081 | 21.765732 | 17.264922 | 8.695808 |
| Logistic Regression Elastic Net   |  0.010747| 472.379882 | 21.734302 | 17.245585 | 8.684373 |
| Polinomial Regression             |  0.066477| 445.768223 | 21.113224 | 16.749939 | 8.547931 |
| Polinomial Regression Ridge       |  0.067695| 445.186573 | 21.099445 | 16.739734 | 8.575067 |
| Polinomial Regression Lasso       |  0.009631| 472.912694 | 21.746556 | 17.238379 | 8.681847 |
| Polinomial Regression Elastic Net |  0.023532| 466.274996 | 21.593402 | 17.102635 | 8.661508 |
  
#### Resultados de Teste para Regressão
| Modelo                            | R2       | MSE        | RMSE      | MAE       | MAPE     |
|-----------------------------------|----------|------------|-----------|-----------|----------|
| Decision Tree                     | 0.036638 | 469.062024 | 21.657840 | 16.822880 | 6.929010 |
| Random Forest                     | 0.353931 | 314.571659 | 17.736168 | 13.020025 | 6.585227 |
| Logistic Regression               | 0.052317 | 461.427719 | 21.480869 | 17.129965 | 8.521859 |
| Logistic Regression Ridge         | 0.052265 | 461.452970 | 21.481456 | 17.128819 | 8.526457 |
| Logistic Regression Lasso         | 0.007646 | 483.177970 | 21.981310 | 17.472989 | 8.753477 |
| Logistic Regression Elastic Net   | 0.010636 | 481.722175 | 21.948170 | 17.447495 | 8.731736 |
| Polinomial Regression             | 0.090079 | 443.041256 | 21.048545 | 16.720535 | 8.242464 |
| Polinomial Regression Ridge       | 0.088422 | 443.848061 | 21.067702 | 16.735629 | 8.304551 |
| Polinomial Regression Lasso       | 0.008372 | 482.824405 | 21.973266 | 17.456854 | 8.756072 |
| Polinomial Regression Elastic Net | 0.021274 | 476.542822 | 21.829861 | 17.313045 | 8.704860 |


### Análise dos Algoritmos de Clusterização

Focamos nos algoritmos K-Means e Affinity Propagation, avaliados pela métrica Silhouette Score:

K-Means: Este algoritmo foi analisado por sua eficácia em agrupar dados em 'K' clusters, com foco em como o número de clusters afeta o desempenho.

Affinity Propagation: Examinou-se este método por sua abordagem distinta na escolha do número de clusters baseado em mensagens passadas entre pares de pontos.

| Modelo               | Número de Clusters| Silhouette score|
|----------------------|-------------------|-----------------|
| K-Means              | 3                 | 0.2329          | 
| Affinity Propagation | 7                 | 0.2036          | 


Cada análise proporcionou insights valiosos sobre o comportamento dos algoritmos em diferentes conjuntos de dados e sob variados parâmetros, essencial para a compreensão de suas aplicações práticas no campo do Machine Learning.

## Resultados e Discussão

A análise comparativa dos algoritmos de Machine Learning revelou insights notáveis. Foi observado que diferentes parâmetros afetam significativamente o desempenho dos algoritmos, destacando a importância do ajuste fino de hiperparâmetros.

### Influência dos Parâmetros:

- Nos algoritmos de classificação, o ajuste do número de vizinhos no KNN e a profundidade da árvore no Decision Tree Classifier mostraram impactos consideráveis na precisão e no recall.
- Em regressão, a regularização em modelos lineares provou ser fundamental na prevenção do overfitting, especialmente em conjuntos de dados com alta dimensionalidade.
- Para os algoritmos de clusterização, a seleção do número de clusters no K-Means influenciou diretamente a pontuação da Silhueta, afetando a clareza da segmentação.

### Padrões e Descobertas:

Algoritmos não-paramétricos como o Random Forest tendem a superar os paramétricos em conjuntos de dados com complexidades variadas.
A eficácia do Affinity Propagation em identificar o número ótimo de clusters foi particularmente notável, sugerindo sua utilidade em aplicações onde a pré-definição de clusters não é viável.

## Conclusões

As descobertas deste estudo sublinham a complexidade e a necessidade de considerar múltiplos aspectos ao aplicar algoritmos de Machine Learning. A escolha e o ajuste de um algoritmo dependem intrinsecamente da natureza do conjunto de dados e do problema específico. Essa compreensão é crucial para avançar no campo do Machine Learning, pois destaca a importância da personalização na aplicação de algoritmos, em vez de depender de abordagens padronizadas.

## Futuras Direções

Para expandir este projeto, propõe-se:

- **Inclusão de Mais Algoritmos:** Testar algoritmos avançados como XGBoost, LightGBM e redes neurais para uma análise mais abrangente.
- **Análise de Conjuntos de Dados Maiores e Mais Diversificados:** Explorar como os algoritmos se comportam em diferentes escalas e tipos de dados.
- **Implementação de Técnicas de Ensemble:** Investigar se a combinação de resultados de múltiplos algoritmos pode levar a uma melhoria na precisão e robustez dos modelos.
- **Estudo de Caso em Aplicações Reais:** Aplicar os algoritmos em problemas do mundo real para validar as descobertas em um contexto prático.

Essas direções podem enriquecer ainda mais o entendimento dos algoritmos de Machine Learning e sua aplicabilidade, contribuindo para o desenvolvimento de soluções mais eficazes e inovadoras no campo.






