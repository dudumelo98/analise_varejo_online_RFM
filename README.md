# analise_varejo_online_RFM

🛍️Análise e Segmentação de Clientes em Varejo Online
Descubra como transformamos dados brutos de transações em insights estratégicos de negócio usando o modelo RFM e Machine Learning.

🎯 Visão Geral: Resolvendo um Problema de Negócio
Todo negócio quer saber: quem são seus melhores clientes?

Este projeto aprofunda-se nos dados de um varejo online para responder uma pergunta muito importante.Através de uma estratégia de ciências de dados,meu objetivo foi:mapear e  analisar  os diferentes perfis de clientes,Organizá-los em grupos com base em seu comportamento de compra,Entregar insights estratégicos para campanhas de marketing personalizadas, promovendo o aumento da retenção e da receita da empresa.

🛠️ Ferramentas e Tecnologias
Linguagem de Programação: Python

Bibliotecas Essenciais: pandas, sqlite3, scikit-learn, matplotlib, datetime

Ambiente de Desenvolvimento: Jupyter Notebook

Banco de Dados: SQLite (para simular a extração de dados real)

📂Dados: O Alicerce da Análise
O centro da nossa análise gira em torno de um conjunto de dados públicos de transações de um varejo online.
 Nome: Online Retail Data
 Fonte: Repositório de Machine Learning da UC Irvine
Licença de Uso: Este conjunto de dados está licenciado sob uma Licença Creative Commons Attribution 4.0 International (CC BY 4.0), e o crédito é dado a Dr. Daqing Chen, do Centre for Business Analytics, University of Westminster.

🚀 Metodologia: A Trajetória dos Dados
Utilizei um fluxo de trabalho padrão para análise de dados, mas com uma abordagem única em cada etapa.
Limpeza de Dados: O tratamento de dados brutos é complexo. Excluímos transações sem CustomerID e devoluções para manter a precisão da análise.
Análise RFM: Adotamos uma nova visão sobre os clientes, calculando suas pontuações de Recência ,tempo desde a última compra, Frequência (quantidade de compras) e Monetariedade (valor total gasto).

Modelagem e Segmentação:
Usei o StandardScaler para preparar os dados.
Apliquei o Método do Cotovelo para selecionar o número ideal de grupos (k=4).
Adotei o algoritmo K-Means de machine learning para dividir os clientes em segmentos.
Análise dos Clusters: Finalmente, analisei as características de cada segmento para dar-lhes "nomes de negócio", como Clientes VIPs ou Clientes em Risco.

📊 Resultados e Próximos Passos
A análise identificou 4 segmentos de clientes distintos e bem definidos:
Cluster 0 (Clientes Fiéis): Compram regularmente e apresentam um alto valor de compras.
Cluster 1 (Clientes Perdidos): Não compram há um longo período e gastaram pouco ao longo do tempo.
Cluster 2 (Clientes VIPs): Os clientes exclusivos. Têm uma frequência de compras altíssima e gastam os maiores valores.
Cluster 3 (Clientes de Médio Valor): O maior grupo de clientes. Realizam compras regulares e gastam valores moderados.

Esses resultados oferecem uma base inicial para a equipe de marketing. Eles podem ser utilizados para:
Criar uma campanha de fidelidade direcionada ao Cluster VIPs.
Enviar propostas de reativação para o Cluster de Clientes Perdidos.
Investigar mais a fundo o comportamento do Cluster de Clientes de Médio Valor.





