# Dashboard_de_Analise_de_venda_ePerformace_comercial_PowerBI

# 📈 Dashboard de Análise de Vendas e Performance Comercial

> **Status:** Concluído ✅

![Preview do Dashboard](PowerBI%201%20imagem.png)

## 💼 Contexto do Negócio

O objetivo deste projeto foi desenvolver uma solução de Business Intelligence para analisar os dados de vendas de uma empresa fictícia. O gerente necessitava de uma visão holística sobre o desempenho comercial para responder a perguntas estratégicas sobre receita, sazonalidade e eficiência da equipe de vendas.

As principais perguntas de negócio respondidas neste relatório foram:
1.  Qual a **receita total** gerada e como ela se comporta mês a mês?
2.  Qual a performance individual de cada **vendedor**?
3.  Quais são os **produtos** com maior saída (volume de vendas)?
4.  Qual é o **Ticket Médio** (Receita Média por Pedido) da operação?

## ⚙️ Funcionalidades e Insights

O painel é interativo e permite análises aprofundadas através de segmentações dinâmicas:

* **KPIs Gerais (Topo):**
    * **Receita Total:** Visão macro do faturamento.
    * **Qtd Pedidos:** Volume transacional.
    * **Qtd Itens:** Total de produtos movimentados.
    * **Ticket Médio:** Indicador de eficiência de vendas (Receita / Pedidos).
* **Análise Temporal:** Gráfico de barras mensal para identificar sazonalidade e tendências de crescimento.
* **Ranking de Vendedores:** Comparativo claro de quem está gerando mais receita.
* **Mix de Produtos:** Análise de volume de vendas por tipo de produto (ex: Smartwatch, Webcam, Tablet).
* **Filtros Laterais:** Capacidade de "fatiar" (drill-down) os dados por **Estado (UF)** e por **Cliente**, permitindo identificar oportunidades regionais.

## 🛠️ Tecnologias e Técnicas Utilizadas

O projeto foi desenvolvido 100% no ecossistema Microsoft Power BI, aplicando as seguintes etapas:

1.  **ETL (Extração, Transformação e Carregamento):**
    * Importação das bases de dados.
    * Tratamento de dados no **Power Query** (limpeza, tipagem de dados, remoção de duplicatas).
2.  **Modelagem de Dados:**
    * Criação de **Relacionamentos** (Esquema Estrela / Star Schema) entre tabelas Fato (Vendas) e Dimensão (Clientes, Produtos, Vendedores, Calendário).
3.  **Cálculos DAX (Data Analysis Expressions):**
    * Criação de Medidas explícitas para os KPIs (Soma, Contagem Distinta, Médias, CALCULATE).
    * Exemplo de lógica usada: `Ticket Médio = DIVIDE([Receita Total], [Qtd Pedidos])`.
4.  **Visualização de Dados (Data Viz):**
    * Design de interface focado em UX (Experiência do Usuário).
    * Uso de tema escuro para destaque das informações.
    * Formatação condicional e alinhamento preciso dos elementos.

## 🚀 Como visualizar este projeto

1.  **Opção 1 (Arquivo Fonte):** Baixe o arquivo `PowerBi 1.pbix` deste repositório e abra-o no Microsoft Power BI Desktop.
2.  **Opção 2 (PDF Estático):** Veja o arquivo `.pdf` exportado (caso tenha anexado) para uma visualização rápida.

---
*Desenvolvido por Bruno Lemos*
*Dúvidas ou sugestões? Entre em contato via [LinkedIn](www.linkedin.com/in/bruno-lemos-dados)*
