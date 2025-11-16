🌸 Classificação de Espécies de Íris com KNN
📘 Descrição do Projeto

Este projeto implementa um sistema de classificação automática de flores do gênero Íris utilizando o algoritmo de aprendizado de máquina K-Nearest Neighbors (KNN).
O trabalho foi desenvolvido como parte da AG2 – Engenharias de Computação e Software do Inatel, seguindo as diretrizes fornecidas pelos professores.

O sistema identifica automaticamente a espécie da flor com base em quatro características botânicas, fornecidas pelo usuário ou presentes no dataset original.

👥 Autores

Henrique Fonseca de Castro

Marcus Vinicius de Faria Junho Filho

🎯 Objetivo Principal

Prever corretamente uma entre três espécies de íris usando suas medidas físicas:

Código → Espécie

1 → Iris Setosa

2 → Iris Versicolor

3 → Iris Virginica

Características utilizadas pelo modelo

🌿 Comprimento da sépala (cm)
🌿 Largura da sépala (cm)
🌺 Comprimento da pétala (cm)
🌺 Largura da pétala (cm)

📊 Sobre o Dataset

Origem: UCI Machine Learning Repository

Coletado por: Ronald Fisher (1936)

Total de amostras: 150

Espécies: 3 classes (50 amostras cada)

Atributos: 4 medidas numéricas por flor

Dataset disponibilizado pelo professor em formato .csv

🧰 Tecnologias Utilizadas

Python 3.11+

Pandas – manipulação e leitura dos dados

NumPy – cálculos auxiliares

Scikit-Learn – construção e avaliação do modelo KNN

Jupyter Notebook – execução e organização do projeto

🛠️ Como Executar o Projeto
🔹 1. Instalar dependências
pip install pandas scikit-learn numpy jupyter

🔹 2. Abrir no VS Code

Abra a pasta do projeto

Instale a extensão Jupyter

Abra o arquivo .ipynb

🔹 3. Executar o notebook

Execute cada célula em ordem até o final.

🚀 Etapas do Desenvolvimento
1. Pré-processamento dos Dados

Leitura do arquivo iris.csv

Conversão da coluna species para valores numéricos:

Iris-setosa → 1

Iris-versicolor → 2

Iris-virginica → 3

2. Separação dos Dados

80% dos dados usados para treinar o modelo

20% reservados para teste

Divisão feita com train_test_split() com embaralhamento aleatório

3. Construção do Modelo KNN

Algoritmo: K-Nearest Neighbors

Número de vizinhos: k = 6

Distância usada: Euclidiana

Modelo treinado com os dados de treino

4. Avaliação

Inclui:

Acurácia no conjunto de teste

Relatório com precision, recall e f1-score

📝 Classificação Manual

O sistema permite que o próprio usuário insira medidas e receba uma previsão imediata.

Exemplo de entrada:
Comprimento da sépala: 5.2
Largura da sépala: 3.4
Comprimento da pétala: 1.5
Largura da pétala: 0.2

Saída esperada:
RESULTADO: A amostra pertence à espécie: Setosa