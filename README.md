


🌸 Classificação de Espécies de Íris com KNN
📘 Descrição do Projeto

Este projeto implementa um sistema de classificação automática de flores do gênero Íris utilizando o algoritmo de aprendizado de máquina K-Nearest Neighbors (KNN).
O trabalho foi desenvolvido como parte da AG2 – Engenharias de Computação e Software (Inatel).

O classificador identifica automaticamente a espécie da flor com base em quatro características botânicas fornecidas pelo usuário ou presentes no dataset.

👥 Autores

Henrique Fonseca de Castro

Marcus Vinicius de Faria Junho Filho

🎯 Objetivo Principal

Prever corretamente uma entre três espécies de íris:

Código	Espécie
1	Iris Setosa
2	Iris Versicolor
3	Iris Virginica
O modelo utiliza as seguintes medidas:

🌿 Comprimento da sépala (cm)

🌿 Largura da sépala (cm)

🌸 Comprimento da pétala (cm)

🌸 Largura da pétala (cm)

📊 Sobre o Dataset

Origem: UCI Machine Learning Repository

Coletado por: Ronald Fisher (1936)

Total: 150 amostras

Espécies: 3 (50 amostras cada)

Atributos: 4 colunas numéricas

Dataset disponibilizado pelo professor.

🧰 Tecnologias Utilizadas

Python 3.11+

Pandas – manipulação de dados

NumPy – apoio matemático

Scikit-Learn – modelo KNN

Jupyter Notebook – ambiente de desenvolvimento

🛠️ Como Executar o Projeto
🔹 1. Instalar dependências
pip install pandas scikit-learn numpy jupyter

🔹 2. Abrir o projeto no VS Code

Abra a pasta do projeto

Instale a extensão Jupyter

Abra o arquivo .ipynb

🔹 3. Executar

Basta rodar as células na ordem.

🚀 Etapas do Desenvolvimento
1. Pré-processamento

Leitura do CSV

Conversão de espécies para valores numéricos:

Iris-setosa → 1

Iris-versicolor → 2

Iris-virginica → 3

2. Separação dos Dados

80% para treino

20% para teste

Separação embaralhada (shuffle=True)

3. Modelo KNN

Algoritmo: K-Nearest Neighbors

Número de vizinhos: k = 6

Distância: Euclidiana

4. Avaliação

Inclui:

Acurácia

Precision / Recall / F1-score

📝 Classificação Manual (Interativa)

O usuário pode inserir as medidas e obter a previsão da espécie.

Exemplo:

Comprimento da sépala: 5.2
Largura da sépala: 3.4
Comprimento da pétala: 1.5
Largura da pétala: 0.2


Resultado:

A amostra pertence à espécie: Setosa
