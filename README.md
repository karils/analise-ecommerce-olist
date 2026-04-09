📊 Análise Exploratória de Dados - E-commerce Brasileiro
📌 Objetivo

Este projeto tem como objetivo aplicar técnicas de análise exploratória de dados em um dataset de e-commerce brasileiro, utilizando ferramentas como Power BI e Looker Studio para identificar padrões, tendências e possíveis melhorias no processo logístico.

📁 Base de Dados

Foi utilizada uma base de dados pública contendo informações sobre pedidos de um e-commerce, incluindo:

Status dos pedidos
Datas de compra e entrega
Datas estimadas de entrega
Identificadores de clientes e pedidos

A base possui grande volume de dados, permitindo análises robustas e representativas.

🔗 Modelagem dos Dados

A análise foi realizada a partir da tabela de pedidos, contendo variáveis relevantes para o entendimento do fluxo logístico.

Foram utilizadas informações como:

order_id
customer_id
order_status
order_purchase_timestamp
order_delivered_customer_date
order_estimated_delivery_date
🧹 Tratamento e Preparação dos Dados

Durante o processo de preparação, foram realizadas as seguintes etapas:

Padronização de formatos de data
Tratamento de valores ausentes
Verificação de inconsistências
🔧 Colunas Criadas

Foram criadas duas colunas derivadas:

delivery_deadline → tempo entre compra e entrega
delay_on_delivery → identifica se o pedido foi entregue com atraso

Essas colunas foram fundamentais para aprofundar a análise.

📊 Análises Exploratórias Realizadas

Foram conduzidas diferentes análises exploratórias, incluindo:

Distribuição dos pedidos por status
Comparação entre pedidos entregues e com problemas
Análise de atrasos nas entregas
Avaliação geral da eficiência logística
Identificação de padrões nos dados
💡 Principais Insights
Aproximadamente 97% dos pedidos foram entregues com sucesso, indicando alta eficiência logística
A maioria dos pedidos concentra-se no status delivered
Os casos de atraso e cancelamento representam uma pequena parcela
A maior parte das entregas ocorre dentro do prazo estimado
O sistema apresenta estabilidade e consistência nos dados
📊 Visualização de Dados

O projeto inclui dashboards desenvolvidos nas seguintes ferramentas:

🔹 Power BI
Visualizações exploratórias
Análise de distribuição e padrões
🔹 Looker Studio
Gráfico de pizza (distribuição dos pedidos)
Gráfico de barras (comparação entre status)
Tabela com contagem de pedidos
Dashboard interativo
🌐 Dashboard Interativo

👉 https://lookerstudio.google.com/reporting/21186652-860d-42f4-a387-ac28be342af2

📄 Relatório

O relatório completo em PDF com todos os detalhes da análise está disponível neste repositório.

🚀 Conclusão

A análise demonstrou que o e-commerce apresenta alto nível de eficiência nas entregas, com predominância de pedidos concluídos com sucesso. Apesar disso, existem oportunidades de melhoria relacionadas a atrasos e cancelamentos, que podem ser trabalhadas para otimizar a experiência do cliente.

🛠️ Ferramentas Utilizadas
Power BI
Looker Studio
Google Sheets / Excel
GitHub
