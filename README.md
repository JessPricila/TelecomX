📊 Análise e Previsão de Churn – TelecomX
📌 Descrição do Projeto

Este projeto tem como objetivo analisar os dados de clientes de uma operadora de telecomunicações (TelecomX) e prever a probabilidade de Churn (cancelamento de serviço).
O dataset contém informações demográficas, serviços contratados, histórico de faturamento e comportamento dos clientes.

A análise inclui:

Exploração e visualização de dados

Criação de novas métricas, como Contas_Diarias (gasto diário médio do cliente)

Relação entre Churn e serviços adicionais

Treinamento de modelo de previsão de Churn usando Random Forest

Avaliação do modelo e análise da importância das features

📁 Dataset

O dataset utilizado está disponível no GitHub:

TelecomX_Data.json

Principais colunas:

customer.tenure – Tempo como cliente

account.Charges.Monthly – Faturamento mensal

account.Charges.Total – Faturamento total

Churn – Indicador de cancelamento

Serviços adicionais: Online Security, Online Backup, Device Protection, Tech Support, Streaming TV, Streaming Movies

🧰 Tecnologias e Bibliotecas

Python 3

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

🚀 Funcionalidades

Exploração e visualização de dados

Estatísticas descritivas

Gráficos de distribuição de churn, tenure e faturamento

Matriz de correlação

Criação da coluna Contas_Diarias

Calcula o gasto diário médio do cliente a partir do faturamento mensal

Análise de Churn vs. Serviços Adicionais

Avalia a influência de serviços como segurança online, backup, proteção de dispositivo, suporte técnico e streaming de TV/filmes

Previsão de Churn com Random Forest

Treinamento do modelo

Avaliação com acurácia, matriz de confusão e relatório de classificação

Análise da importância das features

📊 Insights

Clientes sem serviços essenciais como Segurança Online, Backup, Proteção de Dispositivo e Suporte Técnico apresentam maior probabilidade de churn.

Serviços de entretenimento (Streaming TV/Movies) têm efeito menor na retenção.

A criação de métricas como Contas_Diarias ajuda a entender o comportamento financeiro diário dos clientes.

Estratégias de retenção devem priorizar a oferta e promoção de serviços essenciais.

⚡ Como Executar

Abra o Google Colab

Copie o código do projeto

Execute as células para carregar dados, explorar, analisar e treinar o modelo de churn.
