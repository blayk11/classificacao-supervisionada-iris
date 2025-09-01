# Classificação Supervisionada com Validação Cruzada

Este projeto tem o objetivo de demonstrar um pipeline completo de classificação supervisionada utilizando o algoritmo **Random Forest** com **validação cruzada**.

A idéia é prever a espécie de flores com base em suas características físicas, utilizando o dataset **Iris**.

Dataset utilizado disponibilizado na biblioteca [Scikit-learn](https://scikit-learn.org/stable/).

---

## Estrutura do Projeto

- **Pré-processamento dos dados**
- **Normalização com StandardScaler**
- **Treinamento com RandomForestClassifier**
- **Validação cruzada com 5 folds**
- **Visualização da consistência do modelo com boxplot**

---

## Bibliotecas Utilizadas

- `scikit-learn`
- `pandas`
- `seaborn`
- `matplotlib`

---

## Resultados

- **Acurácia média:** ~90%
- **Variação entre folds:** baixa
- **Conclusão:** O modelo apresenta alta consistência e boa capacidade de generalização, indicando que ele aprende padrões reais e não apenas memoriza os dados.
