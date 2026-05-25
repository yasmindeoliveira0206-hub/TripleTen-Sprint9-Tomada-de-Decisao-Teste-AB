# TripleTen Sprint 9: Tomada de Decisões Baseada em Dados 🧪📊

Este repositório contém o projeto final da nona sprint do curso de Análise de Dados da TripleTen. O foco deste projeto foi a **Tomada de Decisões Baseada em Dados**, utilizando técnicas de priorização de hipóteses e análise rigorosa de **Testes A/B** para uma grande loja online.

## 📋 Contexto do Negócio
Trabalhando em conjunto com o departamento de marketing, o objetivo foi aumentar a receita da loja online através da validação de hipóteses de melhoria no produto. O projeto foi dividido em duas partes principais: a priorização de ideias para testes e a análise dos resultados de um experimento já realizado.

## 🛠️ Tecnologias e Ferramentas
*   **Python 3.x**
*   **Pandas:** Manipulação de dados e cálculos de métricas acumuladas.
*   **NumPy:** Suporte a operações matemáticas e estatísticas.
*   **Matplotlib:** Criação de gráficos de linha para métricas acumuladas e gráficos de dispersão para identificação de outliers.
*   **SciPy (stats):** Realização de testes de significância estatística (Teste de Mann-Whitney).

## 🚀 Desafios Técnicos Superados
Este projeto exigiu uma abordagem analítica completa para garantir a confiabilidade dos resultados:
*   **Priorização de Hipóteses:**
    *   Aplicação dos frameworks **ICE** (Impact, Confidence, Ease) e **RICE** (Reach, Impact, Confidence, Effort).
    *   Análise de como a métrica de "Alcance" (Reach) altera drasticamente a prioridade das tarefas.
*   **Análise de Teste A/B:**
    *   Cálculo e visualização da receita acumulada e do tamanho médio do pedido acumulado por grupo.
    *   Cálculo da conversão acumulada e análise da diferença relativa entre os grupos.
    *   **Tratamento de Outliers:** Identificação de usuários com comportamento atípico (compras excessivas ou valores muito altos) através de percentis (95º e 99º).
*   **Significância Estatística:**
    *   Realização do teste de Mann-Whitney para comparar conversão e tamanho do pedido entre os grupos, tanto com dados "sujos" quanto com dados "filtrados".
    *   Tomada de decisão baseada em p-values e na estabilidade das métricas.

## 📊 Principais Insights
*   Identificação da hipótese vencedora para implementação imediata baseada no score RICE.
*   Conclusão do Teste A/B: O grupo B apresentou uma conversão estatisticamente superior ao grupo A, apesar de não haver diferença significativa no tamanho médio do pedido.
*   Recomendação de interromper o teste e declarar o Grupo B como vencedor, economizando recursos e acelerando a implementação das melhorias.

## 📁 Estrutura do Repositório
*   `notebook.ipynb`: O notebook Jupyter contendo todo o processo de priorização, limpeza, análise acumulada e testes estatísticos.
*   `README.md`: Este arquivo com a apresentação do projeto.

---
*Este projeto faz parte da minha formação como Analista de Dados na TripleTen Brasil.*
