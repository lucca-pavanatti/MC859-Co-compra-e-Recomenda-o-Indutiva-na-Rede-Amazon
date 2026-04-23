# Do Clique ao Carrinho: Anatomia da Co-compra e Recomendação Indutiva na Rede Amazon

Este projeto realiza uma análise detalhada da rede de co-compra da Amazon, utilizando teoria de grafos para entender como produtos se relacionam e como essas conexões podem ser usadas para recomendação.

## 📊 Visão Geral
O projeto utiliza o dataset de metadados de produtos da Amazon (SNAP) para construir redes onde os nós são produtos e as arestas representam relações de co-compra. Exploramos métricas de centralidade, similaridade de Jaccard e detecção de comunidades para extrair insights estruturais da rede.

## 🚀 Funcionalidades
- **Parsing de Dados:** Processamento eficiente do dataset massivo da Amazon.
- **Construção de Grafos:** Implementação de grafos originais e ponderados por similaridade.
- **Análise Estatística:** Métricas de grau, componentes conexas e diâmetro.
- **Centralidade:** Identificação de "produtos-ponte" via Betweenness e PageRank.
- **Comunidades:** Detecção de agrupamentos de produtos usando o algoritmo de Louvain.

## 🛠️ Requisitos
- Python 3.10+
- Bibliotecas: `networkx`, `matplotlib`, `numpy`, `tqdm`, `scikit-learn`, `python-louvain`

## 🏃 Como Usar
1. Instale as dependências:
   ```bash
   pip install networkx matplotlib numpy tqdm scikit-learn community python-louvain
   ```
2. Execute o notebook principal:
   ```bash
   jupyter notebook codigo_fonte.ipynb
   ```

## 📝 Autores
- Alícia Gonçalves Vieira
- Lucca Pavanatti Duarte
