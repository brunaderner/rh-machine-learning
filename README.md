# Análise de Rotatividade de Funcionários (2025)

Este projeto tem como objetivo prever a rotatividade de funcionários em uma organização, utilizando técnicas de machine learning aplicadas a dados de Recursos Humanos. A proposta visa apoiar decisões estratégicas no desenvolvimento e retenção de talentos, antecipando possíveis desligamentos com base em padrões históricos e características dos colaboradores.

## Objetivo

Construir um modelo preditivo supervisionado capaz de identificar os principais fatores associados ao desligamento de funcionários e prever com alta acurácia os casos com maior risco de evasão.

## Tecnologias e Ambiente de Desenvolvimento

- **Linguagem:** Python
- **Bibliotecas:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost
- **Ambiente de Desenvolvimento:** Google Colab
- **Visualização:** Google Slides e matplotlib

## Estrutura

- `dataset/`: Base de dados tratada e explorada
- `notebooks/`: Scripts de análise, visualização e modelagem (.ipynb)
- `presentation/`: Apresentação final com insights (.pdf)

## Metodologia

- **Tratamento dos dados:** Remoção de colunas redundantes, tratamento de variáveis categóricas e criação de novas variáveis como faixa etária.
- **Análise Exploratória:** Visualização da distribuição da variável alvo (Attrition) e cruzamento com variáveis como idade, tempo na empresa, promoções e estado civil.
- **Modelagem:** Aplicação de três modelos: Regressão Logística, Random Forest e XGBoost, com avaliação via AUC, Recall, Accuracy e F1-score.
- **Matriz de Confusão:** Avaliação de falsos positivos e falsos negativos para mensurar risco de decisões equivocadas.
- **Recomendações:** Propostas práticas baseadas em padrões de evasão identificados.

## Principais Resultados

- **XGBoost foi o modelo com melhor desempenho**, apresentando AUC = 0.999, Recall = 97.8% e apenas 3 falsos negativos.
- **Random Forest também se destacou**, com AUC = 0.998 e ótimo equilíbrio entre precisão e recall.
- A **Regressão Logística teve desempenho inferior**, com alta taxa de falsos negativos.
- **Solteiros têm taxa de saída de 35%**, quase três vezes maior que a dos casados (12,7%).
- A maior parte dos desligamentos ocorre nos **primeiros dois anos de empresa**.
- **Funcionários mais jovens** e com **longo tempo sem promoção** também apresentam maiores taxas de rotatividade.

## Recomendações

- **Investir em planos de carreira estruturados**
- **Monitorar perfis de maior risco** (jovens, solteiros, recém-contratados)
- **Incentivar promoções com base em performance**
- **Oferecer bônus de permanência no início da jornada**
- **Utilizar o modelo como ferramenta ativa de RH**

## Apresentação

[Apresentação Final (.pdf)](presentation/bruna-derner-ML05.pdf)

## Vídeo de Apresentação - Loom

Assista à apresentação completa:

[![Assista ao vídeo no Loom](https://img.shields.io/badge/Ver%20Apresenta%C3%A7%C3%A3o-Loom-%23F9C646?style=for-the-badge&logo=loom)](https://www.loom.com/share/81a3c7305b2e403ca918f7cdef8edffc?sid=637c0ff7-5f02-48b2-970e-971aac2acf02)


## Autora

Bruna Derner  
Economista e Analista de Dados  
[LinkedIn](https://www.linkedin.com/in/bruna-derner/)
