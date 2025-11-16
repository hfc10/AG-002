# 🌸 Classificador de Espécies de Íris com KNN

## 📘 Sobre o Projeto

Este projeto apresenta um sistema capaz de identificar automaticamente a
espécie de uma flor do gênero *Íris* utilizando o algoritmo **K-Nearest
Neighbors (KNN)**.\
O desenvolvimento segue os requisitos da AG2 das Engenharias de
Computação e Software do Inatel.

O modelo classifica cada flor com base em quatro medidas fornecidas no
dataset ou inseridas manualmente pelo usuário.

## 👥 Autores

-   **Henrique Fonseca de Castro**\
-   **Marcus Vinicius de Faria Junho Filho**

## 🎯 Objetivo do Sistema

O classificador prevê uma das seguintes espécies:

  Código   Espécie
  -------- -------------------
  **1**    *Iris Setosa*
  **2**    *Iris Versicolor*
  **3**    *Iris Virginica*

A predição é feita analisando:

-   Comprimento da sépala (cm)\
-   Largura da sépala (cm)\
-   Comprimento da pétala (cm)\
-   Largura da pétala (cm)

## 📊 Sobre o Dataset

-   **Origem:** UCI Machine Learning Repository\
-   **Autor da coleta:** Ronald Fisher (1936)\
-   **Total de amostras:** 150\
-   **Classes:** 3 espécies equilibradas (50 cada)\
-   **Atributos:** 4 medidas numéricas por flor\
-   Arquivo em `.csv` disponibilizado pelo professor

## 🧰 Tecnologias Utilizadas

-   **Python 3.11+**\
-   **Pandas** -- manipulação dos dados\
-   **NumPy** -- operações numéricas\
-   **Scikit-Learn** -- modelo KNN e métricas\
-   **Jupyter Notebook** -- ambiente de desenvolvimento

## 🛠️ Como Executar o Projeto

### 🔹 1. Instalar dependências

``` bash
pip install pandas scikit-learn numpy jupyter
```

### 🔹 2. Abrir o projeto no VS Code

1.  Abra a pasta do projeto\
2.  Instale a extensão **Jupyter**\
3.  Abra o arquivo `.ipynb`

### 🔹 3. Executar as células

Execute o notebook de cima para baixo na ordem apresentada.

## 🚀 Etapas do Desenvolvimento

### **1. Pré-processamento**

-   Leitura do arquivo `iris.csv`\
-   Conversão das espécies para números inteiros:
    -   Setosa → **1**\
    -   Versicolor → **2**\
    -   Virginica → **3**

### **2. Separação dos Dados**

-   80% para treino\
-   20% para teste\
-   Divisão aleatória via `train_test_split()`

### **3. Construção do Modelo**

-   Algoritmo: **K-Nearest Neighbors (KNN)**\
-   Número de vizinhos: **k = 6**\
-   Distância utilizada: Euclidiana

### **4. Avaliação**

-   Acurácia do modelo\
-   Relatório com **precision**, **recall** e **f1-score**

## 📝 Classificação Manual

O notebook inclui uma função interativa que permite testar novas
amostras fornecendo manualmente as medidas da flor.

**Exemplo de entrada:**

    Comprimento da sépala: 5.2
    Largura da sépala: 3.4
    Comprimento da pétala: 1.5
    Largura da pétala: 0.2

O sistema retorna a espécie prevista com base no modelo treinado.

## ✔️ Resultado Final

O projeto entrega um classificador funcional, simples de utilizar e fiel
aos requisitos da atividade AG2, permitindo prever espécies de Íris
tanto a partir do dataset quanto por entrada manual do usuário.
