# SQLite-basico

# 📘 Módulo 24 – Bancos de Dados e SQL (SQLite)

Este repositório contém o material prático e os exercícios desenvolvidos durante o **Módulo 24 do curso Profissão Cientista de Dados (EBAC)**, focado em **Bancos de Dados e SQL (SQLite)**.  
O objetivo é aplicar conceitos de **consulta, agregação e manipulação de dados** utilizando a linguagem **SQL** integrada ao ambiente **Python/Pandas**.

---

## 🚀 Tecnologias Utilizadas
- **Python**: Linguagem de programação principal.  
- **Pandas**: Biblioteca para manipulação e análise de dados (DataFrames).  
- **SQLite**: Banco de dados relacional leve, utilizado em memória (`:memory:`) para prática de SQL.  
- **SQL**: Linguagem de consulta estruturada.  

---

## 📂 Estrutura do Projeto
O projeto é composto por um notebook principal e um arquivo de dados:

- `Profissao_Cientista_de_Dados_M24_Pratique.ipynb`: Notebook Jupyter que contém a preparação do ambiente, as consultas SQL resolvidas e questões conceituais.  
- `TB_VENDAS_TAREFA.csv`: Arquivo CSV que é carregado e transformado na tabela `tb_vendas` dentro do banco de dados SQLite.  

---

## ✨ Conteúdo e Exercícios
O notebook aborda a preparação do ambiente de trabalho e a resolução de consultas práticas. Entre os tópicos explorados:

### 🔎 Consultas SQL Práticas
As consultas foram realizadas na tabela de vendas (`tb_vendas`) e cobriram os seguintes pontos:

- Seleção completa de registros (`SELECT *`).  
- Limitação de registros com `LIMIT`.  
- Funções de agregação (`AVG`) para calcular médias de valores e unidades.  
- Criação de colunas derivadas (`VALOR_UNID * UNIDADES` → `VALOR_TOTAL_GASTO`).  
- Desafio: calcular a média total do valor gasto em todos os pedidos.  

### 🧠 Questões Conceituais
Além da prática, o notebook discute conceitos fundamentais, como:

- Vantagens de usar **SQL** em conjunto com **Python**.  
- Diferenças entre **Bancos de Dados Relacionais e Não Relacionais (NoSQL)**.  
- Aplicações do SQL em consultas rápidas no fluxo de análise de dados.  

---

## 💡 Destaques do Projeto
A solução demonstra a capacidade de:

- Conectar uma fonte de dados (`CSV`) a um banco de dados em memória (**SQLite**).  
- Executar consultas SQL com sintaxe padrão (`SELECT, FROM, LIMIT, AS`).  
- Utilizar funções de agregação (`AVG`) para gerar insights a partir dos dados brutos.  
- Criar colunas calculadas diretamente nas queries.  
- Compreender o papel do **SQL e Python** no trabalho de um Cientista de Dados.  

---

✍️ Desenvolvido como parte da formação em **Ciência de Dados - EBAC**.  

