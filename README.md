Consultoria de Dados: Padaria Pão d’Ouro

Este repositório contém o projeto de análise de performance de vendas para a **Padaria Pão d’Ouro**, desenvolvido como parte da atividade de versionamento da **Generation BR**. 

O objetivo principal é atuar como consultor de dados para transformar o histórico de vendas de janeiro de 2024 em visualizações estratégicas, permitindo que o proprietário ajuste estoques e otimize a produção.

---

## Objetivos do Projeto

A análise foi estruturada para responder a três perguntas fundamentais de negócio:

### 1. Tendência de Faturamento
* **Pergunta:** O faturamento da padaria está crescendo ou diminuindo ao longo da semana?
* **Visualização:** Gráfico de linhas exibindo a soma de `Total_Venda` por data.
* **Finalidade:** Identificar sazonalidades e os dias de maior fluxo financeiro.

### 2. Mix de Receita por Categoria
* **Pergunta:** Qual categoria de produto é a mais lucrativa para o negócio?
* **Visualização:** Gráfico de rosca/pizza mostrando a distribuição percentual por categoria (Pães, Confeitaria, Bebidas e Salgados).
* **Finalidade:** Entender quais departamentos sustentam a margem de lucro da empresa.

### 3. Volume de Saída de Produtos
* **Pergunta:** Quais são os produtos mais vendidos em termos de unidade?
* **Visualização:** Gráfico de barras horizontais ordenado de forma decrescente por `Quantidade_Vendida`.
* **Finalidade:** Direcionar o volume de produção para evitar rupturas de estoque dos itens mais populares.

---

## Tecnologias e Ferramentas

Para o desenvolvimento desta solução, foram utilizadas as seguintes ferramentas:

* **Linguagem:** Python
* **Manipulação de Dados:** Pandas
* **Visualização de Dados:** Matplotlib
* **Versionamento:** Git e GitHub

---

## Como visualizar
1. Clone este repositório.
2. Certifique-se de ter o Python e a biblioteca `matplotlib` instalados.
3. Execute o script principal para gerar as visualizações em tempo real.
