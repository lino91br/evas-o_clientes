# evas-o_clientes
desafio ícone Challenge Telecom X: análise de evasão de clientes Challenge Telecom X: análise de evasão de clientes da Alura
📊 TelecomX Churn Guard
Este projeto foi desenvolvido como parte do Alura Challenge Data Science, com o objetivo de reduzir a taxa de evasão (Churn) da empresa fictícia Telecom X.

📋 O Problema de Negócio
A Telecom X apresentava uma perda significativa de clientes. O desafio era identificar padrões no comportamento dos usuários e criar um modelo preditivo que alertasse a equipe de retenção antes que o cancelamento ocorresse.

🛠️ Tecnologias Utilizadas
Linguagem: Python 3.x
Manipulação de Dados: Pandas, NumPy
Visualização: Seaborn, Matplotlib
Machine Learning: Scikit-learn (Random Forest)
Balanceamento de Dados: Imbalanced-learn (SMOTE)
🚀 O Pipeline de Dados
Data Wrangling: Transformação de dados brutos (JSON aninhado) em formato tabular.
Limpeza: Tratamento de valores nulos e correção de tipagem (ex: CobrancaTotal).
EDA: Análise exploratória identificando que contratos mensais e cobranças altas eram os principais gatilhos de churn.
Feature Engineering: Aplicação de One-Hot Encoding e remoção de variáveis irrelevantes.
Handling Imbalance: Aplicação de SMOTE para equilibrar a base de dados, elevando o Recall de 0.47 para 0.57.
📈 Resultados Obtidos
O modelo final de Random Forest obteve um Recall de 57% para a classe de evasão. Isso significa que a solução é capaz de detectar mais da metade dos clientes em risco de saída, permitindo ações preventivas estratégicas.
