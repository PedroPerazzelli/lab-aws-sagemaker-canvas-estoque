PARTE ALTERADA LOGO APOS DESCRIÇÃO DO DESAFIO

# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

Bem-vindo ao desafio de projeto "Previsão de Estoque Inteligente na AWS com SageMaker Canvas. Neste Lab DIO, você aprenderá a usar o SageMaker Canvas para criar previsões de estoque baseadas em Machine Learning (ML). Siga os passos abaixo para completar o desafio!

## 📋 Pré-requisitos

Antes de começar, certifique-se de ter uma conta na AWS. Se precisar de ajuda para criar sua conta, confira nosso repositório [AWS Cloud Quickstart](https://github.com/digitalinnovationone/aws-cloud-quickstart).


## 🎯 Objetivos Deste Desafio de Projeto (Lab)

![image](https://github.com/digitalinnovationone/lab-aws-sagemaker-canvas-estoque/assets/730492/72f5c21f-5562-491e-aa42-2885a3184650)

- Dê um fork neste projeto e reescreva este `README.md`. Sinta-se à vontade para detalhar todo o processo de criação do seu Modelo de ML para uma "Previsão de Estoque Inteligente".
- Para isso, siga o [passo a passo] descrito a seguir e evolua as suas habilidades em ML no-code com o Amazon SageMaker Canvas.
- Ao concluir, envie a URL do seu repositório com a solução na plataforma da DIO.


## 🚀 Passo a Passo

### 1. Selecionar Dataset

-   Navegue até a pasta `datasets` deste repositório. Esta pasta contém os datasets que você poderá escolher para treinar e testar seu modelo de ML. Sinta-se à vontade para gerar/enriquecer seus próprios datasets, quanto mais você se engajar, mais relevante esse projeto será em seu portfólio.
-   Escolha o dataset que você usará para treinar seu modelo de previsão de estoque.
-   Faça o upload do dataset no SageMaker Canvas.

### 2. Construir/Treinar

-   No SageMaker Canvas, importe o dataset que você selecionou.
-   Configure as variáveis de entrada e saída de acordo com os dados.
-   Inicie o treinamento do modelo. Isso pode levar algum tempo, dependendo do tamanho do dataset.

### 3. Analisar

-   Após o treinamento, examine as métricas de performance do modelo.
-   Verifique as principais características que influenciam as previsões.
-   Faça ajustes no modelo se necessário e re-treine até obter um desempenho satisfatório.

### 4. Prever

-   Use o modelo treinado para fazer previsões de estoque.
-   Exporte os resultados e analise as previsões geradas.
-   Documente suas conclusões e qualquer insight obtido a partir das previsões.

## 🤔 Dúvidas?

Esperamos que esta experiência tenha sido enriquecedora e que você tenha aprendido mais sobre Machine Learning aplicado a problemas reais. Se tiver alguma dúvida, não hesite em abrir uma issue neste repositório ou entrar em contato com a equipe da DIO.


DESAFIO

Passo a Passo
1. Selecionar Dataset
•	Navegue até a pasta datasets deste repositório. Esta pasta contém datasets que você poderá usar para treinar e testar seu modelo de ML. Sinta-se à vontade para gerar/enriquecer seus próprios datasets.
•	Escolha o dataset que você usará para treinar seu modelo de previsão de estoque.
•	Faça o upload do dataset no SageMaker Canvas.
2. Construir e Treinar
•	No SageMaker Canvas, importe o dataset que você selecionou.
•	Configure as variáveis de entrada e saída de acordo com os dados.
•	Inicie o treinamento do modelo. Isso pode levar algum tempo, dependendo do tamanho do dataset.
3. Analisar
•	Após o treinamento, examine as métricas de performance do modelo.
•	Verifique as principais características que influenciam as previsões.
•	Faça ajustes no modelo, se necessário, e re-treine até obter um desempenho satisfatório.
4. Prever
•	Use o modelo treinado para fazer previsões de estoque.
•	Exporte os resultados e analise as previsões geradas.
•	Documente suas conclusões e qualquer insight obtido a partir das previsões.

1. Selecionar Dataset
Selecionei o DATASET de dataset-1000-com-preco-promocional-e-renovacao-estoque
2. Construir e Treinar
No Sage Maker importei o Dataset e selecionei a coluna quantidade de Estoque para predict e no Model type selecionei o ID do produto column that uniquely identifies the items in your dataset eo Preço na coluna de valores eo Data Events no time stamps
E coloquei no simples

3. Analisar
A função AVG (média) no SQL calcula a média aritmética de um conjunto de valores numéricos numa coluna de uma tabela A função AVG (média) no SQL calcula a média aritmética de um conjunto de valores numéricos numa coluna de uma tabela
Avg. wQL
0.379

MAPE é a sigla para Mean Absolute Percentage Error, ou Erro Percentual Absoluto Médio
MAPE
0.428

WAPE é a sigla para Weighted Absolute Percentage Error (Erro Percentual Absoluto Ponderado, em português)
WAPE
0.539

RMSE é a sigla para Root Mean Square Error (Erro Quadrático Médio, em português). É uma métrica comum usada para medir a precisão de modelos de previsão ou regressão. O RMSE calcula a média das diferenças ao quadrado entre os valores previstos e os valores reais, e depois tira a raiz quadrada dessa média.
RMSE
25.872

MASE é a sigla para Mean Absolute Scaled Error (Erro Absoluto Médio Escalonado, em português). É uma métrica de avaliação de previsões que é menos sensível aos outliers e que permite comparações entre séries temporais com diferentes escalas e unidades.
MASE
0.569
O ANALISADO E QUE OS PRODUTOS COM PROMOÇÕES SÃO OS QUE MAIS VENDEM LOGO A PROMOÇÃO E UMA PARTE MUITO IMPORTANTE  NAS VENDAS 
EO PREÇO DO PRODUTO TAMBEM PARECE AFETALO

4. Prever
PREVEJO QUE  O 1013 VA CHEGAR A 0 PRIMEIRO QUE OS OUTROS EM ESTOQUE E QUE ELE E UM DOS NOSSOS PRODUTOS MAIS VENDIDOS



1. Selecionar Dataset
Selecionei o DATASET de dataset-1000-com-preco-promocional-e-renovacao-estoque
2. Construir e Treinar
No Sage Maker importei o Dataset e selecionei a coluna quantidade de Estoque para predict e no Model type selecionei o ID do produto column that uniquely identifies the items in your dataset eo Preço na coluna de valores eo Data Events no time stamps
E coloquei no Standart 1-4 HOURS

Avg. wQL
1.006
MAPE
1.000
WAPE
1.000
RMSE
8.534
MASE
0.132
E deu uma grande correlação com  Descontos e promoções 
Model status
Standard build
Avg. wQL
0.478
MAPE
0.541
WAPE
0.749
RMSE
31.266
MASE
0.995


4. Prever
PREVEJO QUE  O 1013 VA CHEGAR A 0 PRIMEIRO QUE OS OUTROS EM ESTOQUE E QUE ELE E UM DOS NOSSOS PRODUTOS MAIS VENDIDOS









