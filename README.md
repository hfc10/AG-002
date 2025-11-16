🌸 Classificação de Espécies de Íris com KNN
📘 Descrição do Projeto

Este projeto implementa um sistema de classificação automática de flores do gênero Íris utilizando o algoritmo de aprendizado de máquina K-Nearest Neighbors (KNN).
O trabalho foi desenvolvido como parte da AG2 – Engenharias de Computação e Software (Inatel), seguindo as diretrizes fornecidas pelos professores.

O classificador identifica automaticamente a espécie da flor com base em quatro características botânicas, fornecidas pelo usuário ou presentes no conjunto de dados original.

👥 Autores

Henrique Fonseca de Castro

Marcus Vinicius de Faria Junho Filho

🎯 Objetivo Principal

Prever corretamente uma entre três espécies de íris, utilizando suas medidas físicas:

Código	Espécie
1	Iris Setosa
2	Iris Versicolor
3	Iris Virginica

As previsões são feitas com base nas seguintes características:

🌿 Comprimento da sépala (cm)
🌿 Largura da sépala (cm)
🌺 Comprimento da pétala (cm)
🌺 Largura da pétala (cm)

📊 Sobre o Dataset

Origem: UCI Machine Learning Repository

Coletado por: Ronald Fisher (1936)

Total: 150 amostras

Classes: 3 espécies (50 amostras cada)

Atributos: 4 medidas numéricas por flor

Dataset disponibilizado em formato .csv para uso no projeto.

🧰 Tecnologias Utilizadas

Python 3.11+

Pandas – manipulação dos dados

NumPy – cálculos numéricos

Scikit-Learn – modelo KNN e métricas

Jupyter Notebook – ambiente de desenvolvimento

🛠️ Como Executar o Projeto
🔹 1. Instalar dependências
pip install pandas scikit-learn numpy jupyter

🔹 2. Abrir o projeto (VS Code)

Abra a pasta do projeto

Instale a extensão Jupyter

Abra o arquivo .ipynb

🔹 3. Executar

Rode as células do notebook na ordem apresentada.

🚀 Etapas do Desenvolvimento
1. Pré-processamento dos Dados

Leitura do arquivo iris.csv

Conversão das espécies em valores numéricos:

Iris-setosa → 1

Iris-versicolor → 2

Iris-virginica → 3

2. Separação dos Dados

Divisão em 80% treino e 20% teste

Embaralhamento com train_test_split()

3. Construção do Modelo KNN

Algoritmo: K-Nearest Neighbors

Número de vizinhos: k = 6

Distância Euclidiana para comparação

4. Avaliação

Acurácia do modelo

Relatório de classificação com:

Precision

Recall

F1-score

📝 Classificação Manual Interativa

O projeto possui uma função que permite ao usuário digitar medidas da flor e obter a espécie prevista.

Exemplo:

Comprimento da sépala: 5.2
Largura da sépala: 3.4
Comprimento da pétala: 1.5
Largura da pétala: 0.2


Resultado:
→ A amostra pertence à espécie: Iris Setosa
