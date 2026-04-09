# 📊 Análise Exploratória de Dados - E-commerce Brasileiro (Olist)

## 📌 Sobre o Projeto

Este projeto tem como objetivo realizar uma análise exploratória de dados a partir de um dataset público de e-commerce brasileiro, disponibilizado pela plataforma Olist.

A análise foi desenvolvida com foco em compreender o comportamento dos pedidos, avaliar a eficiência logística e identificar possíveis oportunidades de melhoria.

---

## 📁 Base de Dados

O dataset utilizado contém mais de **100 mil pedidos realizados entre 2016 e 2018**, incluindo informações sobre clientes, pedidos e entregas. ([Kaggle][1])

Principais variáveis utilizadas:

* Status dos pedidos
* Datas de compra e entrega
* Datas estimadas de entrega
* Identificação de clientes

---

## 🔗 Modelagem dos Dados

A análise foi baseada na tabela de pedidos (`orders`), contendo dados essenciais para avaliação do fluxo logístico.

Campos principais:

* `order_id`
* `customer_id`
* `order_status`
* `order_purchase_timestamp`
* `order_delivered_customer_date`
* `order_estimated_delivery_date`

---

## 🧹 Tratamento e Preparação dos Dados

Foram realizadas as seguintes etapas:

* Padronização de formatos de data
* Tratamento de valores ausentes
* Verificação de inconsistências

### 🔧 Colunas Derivadas

Foram criadas novas colunas para enriquecer a análise:

* `delivery_deadline` → tempo entre compra e entrega
* `delay_on_delivery` → identifica atrasos

---

## 📊 Análises Exploratórias

As análises realizadas incluíram:

* Distribuição dos pedidos por status
* Comparação entre pedidos entregues e com problemas
* Análise de atrasos nas entregas
* Avaliação da eficiência logística
* Identificação de padrões nos dados

---

## 💡 Principais Insights

* Aproximadamente **97% dos pedidos foram entregues com sucesso**, indicando alta eficiência logística
* A maioria dos pedidos está concentrada no status *delivered*
* Casos de atraso e cancelamento são minoritários
* A maior parte das entregas ocorre dentro do prazo estimado
* O sistema apresenta estabilidade e consistência

---

## 📊 Visualizações

### 🔹 Power BI

* Análise exploratória dos dados
* Identificação de padrões e distribuição

### 🔹 Looker Studio

* Gráfico de pizza (distribuição dos pedidos)
* Gráfico de barras (comparação de status)
* Tabela com contagem de pedidos

---

## 🌐 Dashboard Interativo

👉 https://lookerstudio.google.com/u/0/reporting/21186652-860d-42f4-a387-ac28be342af2/page/UqiuF

---

## 📄 Relatório

O relatório completo com a análise detalhada está disponível neste repositório em formato PDF.

---

## 🚀 Conclusão

Os resultados indicam que o e-commerce apresenta alto nível de eficiência operacional, com predominância de entregas bem-sucedidas. No entanto, pequenas ocorrências de atraso e cancelamento apontam oportunidades de melhoria nos processos logísticos.

---

## 🛠️ Ferramentas Utilizadas

* Power BI
* Looker Studio
* Google Sheets
* GitHub

---

## 👩‍💻 Autora

Projeto desenvolvido como parte do curso de Analista de Dados.

[1]: https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce?utm_source=chatgpt.com "Brazilian E-Commerce Public Dataset by Olist"

