# SQLite-basico

Este repositório contém o material prático e os exercícios desenvolvidos durante o Módulo 24 do curso de Profissão Cientista de Dados, focado em Bancos de Dados e SQL (SQLite). O objetivo é aplicar conceitos de consulta, agregação e manipulação de dados utilizando a linguagem SQL e o ambiente Python/Pandas.

🚀 Tecnologias Utilizadas
Python: Linguagem de programação principal.

Pandas: Biblioteca para manipulação e análise de dados (DataFrames).

SQLite: Banco de dados relacional leve utilizado em memória (:memory:) para a prática de SQL.

SQL: Linguagem de consulta estruturada.

📂 Estrutura do Projeto
O projeto é composto por um notebook principal e um arquivo de dados:

Profissao_Cientista_de_Dados_M24_Pratique.ipynb: O notebook Jupyter que contém todo o código de conexão, as consultas SQL resolvidas e as questões conceituais.

TB_VENDAS_TAREFA.csv: Arquivo CSV que é carregado e transformado na tabela tb_vendas no banco de dados SQLite.

✨ Conteúdo e Exercícios
O notebook aborda a preparação do ambiente e a resolução de uma série de exercícios práticos e conceituais:

Consultas SQL Práticas
As consultas foram realizadas na tabela de vendas (tb_vendas) e cobriram os seguintes tópicos:

Seleção Completa: Retornar todas as colunas e linhas.

Limitação de Registros: Consultar um número específico de linhas (LIMIT).

Funções de Agregação (Média): Calcular a média de VALOR_UNID e UNIDADES (AVG).

Criação de Colunas Derivadas: Multiplicar colunas (VALOR_UNID * UNIDADES) e renomear com AS para obter o VALOR_TOTAL_GASTO.

Desafio - Média Total Agregada: Calcular a média do valor total gasto em todos os pedidos.

Questões Conceituais
Além da prática com SQL, foram abordados e discutidos os seguintes temas:

Utilidade do SQL vs. Python para a Ciência de Dados.

Diferenciação entre Bancos de Dados Relacionais e Não Relacionais (NoSQL).

Argumentação sobre a praticidade do SQL para consultas rápidas.

💡 Destaques do Projeto
A solução demonstra a capacidade de:

Conectar uma fonte de dados (CSV) a um banco de dados em memória (SQLite).

Executar consultas SQL com sintaxe padrão (SELECT, FROM, LIMIT, AS).

Utilizar funções de agregação (AVG) para gerar insights a partir dos dados brutos.

Realizar operações aritméticas (*) diretamente na consulta SQL.

Compreender e articular a função das principais ferramentas (SQL e Python) no fluxo de trabalho de um Cientista de Dados.
