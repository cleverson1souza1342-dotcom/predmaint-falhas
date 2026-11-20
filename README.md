# Análise preditiva de falhas de manutenção

## Objetivo
Este projeto compara modelos de aprendizado de máquina para identificar possíveis falhas em equipamentos industriais a partir de dados de sensores.

## Arquivos
- `projeto.ipynb`: análise, preparação dos dados e comparação dos modelos.
- `dados/`: base de dados utilizada no projeto.

## Etapas
O notebook apresenta a análise exploratória, o tratamento dos dados, a criação de uma variável, a divisão entre treino e teste, o treinamento dos modelos KNN e árvore de decisão e a avaliação dos resultados.

## Resultados
No conjunto de teste, a árvore de decisão obteve acurácia de 93,05% e recall aproximado de 69,1%. O KNN obteve acurácia de 90,55% e recall aproximado de 64,7%. Como os dados são desbalanceados, a acurácia deve ser interpretada com cautela.

## Como executar
1. Instale as dependências listadas em `requirements.txt`.
2. Abra `projeto.ipynb` no Jupyter ou no VS Code.
3. Execute as células em ordem e confira o caminho relativo da base de dados.

## Melhorias futuras
Testar outros modelos, usar validação cruzada e comparar métricas adicionais, como precisão e F1-score.
