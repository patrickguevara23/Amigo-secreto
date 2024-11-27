Este projeto utiliza algoritmos de Machine Learning para prever se uma pessoa tem ou não diabetes com base em dados clínicos. Os modelos foram treinados e avaliados utilizando um conjunto de dados contendo variáveis de saúde de pacientes. O objetivo é fornecer uma abordagem eficaz para auxiliar na tomada de decisões médicas.

🔍 Descrição do Projeto

A predição é feita a partir de variáveis clínicas como idade, índice de massa corporal (IMC), pressão arterial, entre outros. Foi realizada uma análise exploratória e o pré-processamento dos dados para garantir a qualidade das informações usadas nos modelos.

Os valores de saída (target) estão definidos como:

0: Não possui diabetes

1: Possui diabetes

⚙️ Técnicas e Algoritmos Utilizados

Modelos de Machine Learning:

K-Nearest Neighbors (KNN)

Árvore de Decisão

Modelo Dummy (baseline)

Support Vector Classification (SVC)

Pré-processamento:

Limpeza de dados

Tratamento de valores ausentes

Escalonamento de variáveis (quando necessário)



🛠️ Ferramentas e Tecnologias

Linguagem: Python

Bibliotecas:

Pandas

NumPy

Scikit-learn

Statsmodel

Scipy



🧪 Estrutura do Projeto

├── data/             # Conjunto de dados utilizado no projeto

├── Projeto_Diabetes.ipynb/        # Notebooks com análise exploratória e modelos

└── README.md         # Documentação do projeto


