🌸 Classificação de Espécies de Íris com KNN
📘 Descrição do Projeto

Este trabalho implementa um sistema de classificação automática de flores do gênero Íris utilizando o algoritmo K-Nearest Neighbors (KNN).
O projeto foi desenvolvido como parte da AG2 das Engenharias de Computação e Software do Inatel, seguindo os requisitos apresentados pelos professores.

O classificador identifica a qual espécie a flor pertence com base em quatro medidas botânicas fornecidas pelo usuário ou contidas no dataset original.

👥 Autores

Henrique Fonseca de Castro
Marcus Vinicius de Faria Junho Filho

🎯 Objetivo Principal

O objetivo é prever corretamente uma entre três espécies de íris, a partir de suas medidas:

Código	Espécie
1	Iris Setosa
2	Iris Versicolor
3	Iris Virginica
As previsões são feitas usando:

Comprimento da sépala (cm)

Largura da sépala (cm)

Comprimento da pétala (cm)

Largura da pétala (cm)

📊 Sobre o Dataset

Origem: UCI Machine Learning Repository

Coletado por: Ronald Fisher (1936)

Total: 150 amostras

Classes: 3 espécies com 50 amostras cada

Atributos: 4 medidas numéricas por flor

Dataset utilizado no formato .csv disponibilizado pelo professor.

🧰 Tecnologias Utilizadas

Python 3.11+

Pandas – manipulação dos dados

NumPy – cálculos numéricos auxiliares

Scikit-Learn – treinamento e avaliação do modelo KNN

Jupyter Notebook – ambiente de desenvolvimento

🛠️ Como Executar o Projeto
🔹 1. Instalar dependências

Use o comando abaixo no terminal:

pip install pandas scikit-learn numpy jupyter

🔹 2. Abrir o projeto

Se estiver usando VS Code:

Abra a pasta do projeto

Instale a extensão "Jupyter"

Abra o arquivo .ipynb

🔹 3. Rodar o notebook

Execute as células do notebook na ordem apresentada.

🚀 Etapas do Desenvolvimento
1. Pré-processamento dos Dados

Leitura do arquivo iris.csv

Conversão da coluna species em valores numéricos:

Iris-setosa → 1

Iris-versicolor → 2

Iris-virginica → 3

2. Separação dos Dados

80% usados para treinar o modelo

20% reservados para teste

Divisão aleatória realizada com train_test_split()

3. Construção do Modelo KNN

Algoritmo escolhido: K-Nearest Neighbors

Número de vizinhos: k = 6 (valor ajustado para o projeto)

Cálculo da distância Euclidiana para determinar a classe mais próxima

4. Avaliação

Inclui:

Acurácia do modelo no conjunto de teste

Relatório contendo precision, recall e f1-score

📝 Como Utilizar a Classificação Manual

O projeto inclui uma função interativa que permite ao usuário digitar as medidas da flor para obter a espécie prevista.

Exemplo de uso:

Comprimento da sépala: 5.2
Largura da sépala: 3.4
Comprimento da pétala: 1.5
Largura da pétala: 0.2


A saída será semelhante a:

A flor foi classificada como: Virginica
