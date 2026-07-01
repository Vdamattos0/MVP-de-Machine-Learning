# MVP de Machine Learning 

## Tema
Previsão de adesão a depósito a prazo.

## Objetivo
Desenvolver um modelo de classificação supervisionada capaz de prever se um cliente irá aderir ou não a um depósito a prazo com base em dados históricos de campanhas de marketing bancário.

## Dataset
Foi utilizado o dataset **Bank Marketing**, disponível na **UCI Machine Learning Repository**.

Fonte oficial:
https://archive.ics.uci.edu/dataset/222/bank+marketing

## Arquivos do repositório
- `mvp_machine_learning.ipynb`: notebook principal do MVP
- `bank-full.csv`: dataset utilizado no notebook

## Abordagem
No notebook foram realizadas as seguintes etapas:
- definição do problema
- apresentação e inspeção dos dados
- análise exploratória inicial
- preparação dos dados com pipeline
- divisão entre treino e teste
- treinamento de baseline e modelos candidatos
- ajuste de hiperparâmetros
- avaliação e conclusão final

## Melhor modelo
O melhor desempenho foi obtido com o modelo **RandomForest Tunado**.

## Notebook
O notebook pode ser acessado diretamente neste repositório:
`mvp_machine_learning.ipynb`
