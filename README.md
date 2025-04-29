# 🧠 Predição de Recorrência de Câncer de Mama com KNN

Este projeto tem como objetivo aplicar algoritmos de **Machine Learning** para **prever a recorrência de câncer de mama** com base em dados clínicos de pacientes. A abordagem utiliza o algoritmo **K-Nearest Neighbors (KNN)** para realizar a classificação entre pacientes com e sem recorrência.

---

## 🗂️ Sobre o Dataset

O conjunto de dados utilizado foi obtido do repositório [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer). Ele contém variáveis clínicas como:

- Idade
- Estágio da menopausa
- Tamanho do tumor
- Número de linfonodos afetados
- Localização do tumor na mama
- Irradiação
- Entre outras

---

## 🎯 Objetivo

> Utilizar técnicas de inteligência artificial para **classificar pacientes entre aqueles com e sem recorrência de câncer de mama**, a partir de características clínicas simples, com foco em auxiliar decisões médicas preventivas.

---

## ⚙️ Etapas do Projeto

- 📌 Carregamento e exploração dos dados
- 🧹 Tratamento de valores faltantes e codificação de variáveis categóricas
- 🔢 Transformação de intervalos em valores numéricos médios
- ⚖️ Normalização das variáveis numéricas
- 🧪 Divisão entre treino e teste
- 🔍 Aplicação do algoritmo KNN
- 📊 Avaliação com diferentes métricas:
  - Matriz de confusão
  - Acurácia
  - Precision, Recall, F1-score
- 📈 Otimização do valor de `k` usando:
  - Elbow Method
  - Cross-validation
  - Heurística empírica (√n)

---

## 📊 Resultados

O modelo foi avaliado para diversos valores de `k`, e o melhor desempenho foi obtido com `k = X` *(substitua depois)*, com acurácia de aproximadamente `YY%`. O modelo demonstrou boa capacidade de generalização e diferenciação entre os casos com e sem recorrência.

---
