# Análise de Vendas para E-commerce (EDA)

Análise exploratória e visualização de dados de vendas de e-commerce desenvolvida em Python. O projeto simula o ciclo completo de análise de dados: desde a geração de registros fictícios e pré-processamento até o levantamento de indicadores-chave de desempenho (KPIs) para apoio à tomada de decisão estratégica.

---

## 📌 Contexto do Negócio

Uma operação de e-commerce em expansão necessita de visibilidade clara sobre o desempenho de suas vendas para resolver gargalos estratégicos:
* **Gestão de Estoque:** Identificação dos itens de alta e baixa rotatividade.
* **Planejamento Financeiro:** Acompanhamento da evolução do faturamento ao longo do tempo.
* **Estratégia Geográfica:** Mapeamento das regiões de maior representatividade na receita.
* **Categorização do Portfólio:** Entendimento de quais segmentos impulsionam o negócio.

---

## 🛠️ Tecnologias e Bibliotecas

* **Linguagem:** Python
* **Manipulação de Dados:** Pandas, NumPy
* **Visualização de Dados:** Matplotlib, Seaborn
* **Geração e Formatação de Dados:** `datetime`, `random`, `watermark`

---

## ⚙️ Fluxo de Trabalho e Engenharia de Dados

1. **Geração de Dados Sintéticos:** Criação de um conjunto de dados simulando transações com atributos como `ID_Pedido`, `Data_Pedido`, `Nome_Produto`, `Categoria`, `Preco_Unitario`, `Quantidade`, `Cidade` e `Estado`.
2. **Engenharia de Atributos:**
   * Cálculo da receita total por transação (`Faturamento = Preco_Unitario * Quantidade`).
   * Classificação do status de entrega com base na localização geográfica.
   * Extração e conversão de períodos temporais para agrupamentos mensais (`YYYY-MM`).
3. **Análise Exploratória e Agrupamentos:** Agregações por produto, categoria, estado e janela temporal para responder às perguntas do negócio.

---

## 📊 Principais Visualizações

O notebook inclui quatro análises visuais focadas em respostas diretas para o negócio:

* **Top 10 Produtos Mais Vendidos:** Gráfico de barras horizontais detalhando os itens com maior volume de vendas.
* **Evolução do Faturamento Mensal:** Gráfico de linha temporal com marcadores demonstrando a tendência de receita ao longo dos meses.
* **Faturamento por Estado:** Gráfico de barras destacando a concentração regional da receita.
* **Faturamento por Categoria:** Gráfico de barras com formatação personalizada no eixo de valores (escala em milhares - K) para facilitar a leitura executiva.

---

EM ANDAMENTO...
