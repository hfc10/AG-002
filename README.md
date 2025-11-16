🌸 Classificação de Espécies de Íris com KNN
📘 Descrição do Projeto
Este projeto implementa um sistema de classificação automática para flores do gênero Íris utilizando o algoritmo de aprendizado de máquina K-Nearest Neighbors (KNN).

O trabalho foi desenvolvido para a AG2 – Engenharias de Computação e Software (Inatel), seguindo as diretrizes apresentadas pelos professores. O classificador identifica, automaticamente, a espécie da flor com base em quatro medidas botânicas fornecidas pelo usuário ou pelo dataset original.

👥 Autores
Henrique Fonseca de Castro

Marcus Vinicius de Faria Junho Filho

🎯 Objetivo Principal
Prever corretamente uma das três espécies de Íris, utilizando suas medidas físicas:

Código	Espécie
1	Iris Setosa
2	Iris Versicolor
3	Iris Virginica
✨ Características utilizadas na previsão (Features)
🌿 Comprimento da sépala (cm)

🌱 Largura da sépala (cm)

🌸 Comprimento da pétala (cm)

🌺 Largura da pétala (cm)

📊 Sobre o Dataset
Origem: UCI Machine Learning Repository

Coletado por: Ronald Fisher (1936)

Amostras Totais: 150

Classes: 3 (50 de cada espécie)

Atributos: 4 medidas numéricas por flor

Fonte: Dataset fornecido em formato .csv pelo professor.

🧰 Tecnologias Utilizadas
Python 3.11+

Pandas – Manipulação dos dados

NumPy – Cálculos numéricos

Scikit-Learn – Treinamento e avaliação do modelo KNN

Jupyter Notebook – Ambiente de desenvolvimento

🛠️ Como Executar o Projeto
🔹 1. Instalar dependências
Execute o comando no terminal:

Bash
pip install pandas scikit-learn numpy jupyter
🔹 2. Abrir o projeto no VS Code
Abra a pasta do projeto.

Instale a extensão Jupyter.

Abra o arquivo .ipynb.

🔹 3. Rodar o notebook
Execute as células na ordem apresentada.

🚀 Etapas do Desenvolvimento
1. Pré-processamento dos Dados
Leitura do arquivo iris.csv.

Conversão da coluna species em valores numéricos:

Setosa → 1

Versicolor → 2

Virginica → 3

2. Separação dos Dados
80% para treinamento.

20% para teste.

Divisão realizada com a função train_test_split().

3. Construção do Modelo KNN
Algoritmo: K-Nearest Neighbors.

Valor de k utilizado: 6.

Métrica de Distância: Euclidiana.

4. Avaliação
O modelo inclui métricas de desempenho no conjunto de teste:

Acurácia.

Relatório com precision, recall e f1-score.

📝 Classificação Manual (Interativa)
O projeto possui uma função que recebe as medidas fornecidas pelo usuário e retorna a espécie prevista.

Exemplo de entrada:

Comprimento da sépala: 5.2 Largura da sépala: 3.4 Comprimento da pétala: 1.5 Largura da pétala: 0.2

RESULTADO: A amostra pertence à espécie: Setosa
