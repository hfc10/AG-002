🌸 Classificação de Espécies de Íris com KNN
📘 Descrição do Projeto

Este projeto implementa um sistema de classificação automática de flores do gênero Íris, utilizando o algoritmo de aprendizado de máquina K-Nearest Neighbors (KNN).
O trabalho foi desenvolvido como parte da AG2 – Engenharias de Computação e Software (Inatel), seguindo as diretrizes fornecidas pelos professores.

O classificador identifica automaticamente a espécie da flor com base em quatro características botânicas, fornecidas pelo usuário ou pelo conjunto de dados.

👥 Autores

Henrique Fonseca de Castro

Marcus Vinicius de Faria Junho Filho

🎯 Objetivo Principal

Prever corretamente uma entre três espécies de íris, utilizando suas medidas físicas:

Código	Espécie
1	Iris Setosa
2	Iris Versicolor
3	Iris Virginica

As previsões do modelo são feitas com base nas seguintes características:

🌿 Comprimento da sépala (cm)

🌿 Largura da sépala (cm)

🌸 Comprimento da pétala (cm)

🌸 Largura da pétala (cm)

📊 Sobre o Dataset

Origem: UCI Machine Learning Repository

Coletado por: Ronald Fisher (1936)

Total de amostras: 150

Classes: 3 espécies (50 amostras cada)

Atributos: 4 medidas numéricas por flor

Formato: arquivo .csv disponibilizado pelo professor

🧰 Tecnologias Utilizadas

🐍 Python 3.11+

📊 Pandas – manipulação dos dados

🔢 NumPy – cálculos numéricos auxiliares

🤖 Scikit-Learn – treinamento, teste e métricas do modelo

📓 Jupyter Notebook – ambiente de desenvolvimento do projeto

🛠️ Como Executar o Projeto
🔹 1. Instalar dependências

Execute no terminal:

pip install pandas scikit-learn numpy jupyter

🔹 2. Abrir o projeto no VS Code

Abra a pasta do projeto

Instale a extensão Jupyter

Abra o arquivo .ipynb

Execute as células na ordem

🔹 3. Executar o Notebook

Cada bloco contém uma etapa do processo:

Carregamento dos dados

Pré-processamento

Divisão treino/teste

Treinamento do modelo

Avaliação

Classificação interativa

🚀 Etapas do Desenvolvimento
1. Pré-processamento

Leitura do arquivo iris.csv

Conversão da coluna species para números:

Iris-setosa → 1

Iris-versicolor → 2

Iris-virginica → 3

2. Separação dos Dados

80% usados para treinamento

20% usados para teste

Divisão realizada com train_test_split()

Embaralhamento ativado conforme exigido pelo PDF

3. Construção do Modelo KNN

Algoritmo: K-Nearest Neighbors

Número de vizinhos: k = 6

Distância utilizada: Euclidiana

Modelo treinado com os dados de treino

4. Avaliação

O sistema exibe:

✔️ Acurácia no conjunto de teste

✔️ Relatório contendo precision, recall e f1-score

📝 Classificação Manual (Interativa)

O projeto conta com uma função que permite ao usuário digitar medidas reais de uma flor para classificá-la.

Exemplo de entrada:

Comprimento da sépala: 5.2
Largura da sépala: 3.4
Comprimento da pétala: 1.5
Largura da pétala: 0.2


Saída esperada:

A amostra pertence à espécie: Setosa
