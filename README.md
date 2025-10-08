# 📊 Segmentação de Clientes com Técnicas de Aprendizado Não Supervisionado

Este projeto tem como objetivo identificar padrões de comportamento entre consumidores de um e-commerce utilizando **métodos de aprendizado não supervisionado**, com foco na **segmentação de clientes via K-Means**.

O estudo utiliza o conjunto de dados **E-commerce Sales Transactions Dataset** (Kaggle), que contém milhares de registros de vendas, incluindo informações sobre perfil do cliente, categorias de produtos e métricas financeiras.

---

## 🚀 Objetivos

- Explorar padrões de consumo e desempenho de vendas por categoria, região e gênero.  
- Calcular indicadores como **lucro médio**, **volume de vendas** e **margem percentual**.  
- Aplicar o algoritmo **K-Means** para **segmentar clientes** com base em comportamento e rentabilidade.  
- Avaliar o número ideal de clusters usando **inertia** e **silhouette score**.  
- Visualizar e interpretar os clusters para identificar **perfis e oportunidades de marketing**.

---

## 🧠 Metodologia

### 1. Pré-processamento dos dados
- Tratamento de valores ausentes e duplicados.  
- Criação de variáveis derivadas (ex.: lucro percentual, total gasto).  
- Codificação de variáveis categóricas e normalização com *StandardScaler*.

### 2. Análise Exploratória (EDA)
- Análise das distribuições de lucro, descontos e volume de vendas.  
- Comparação de desempenho entre categorias e regiões.  
- Visualização temporal do lucro e das vendas.

### 3. Modelagem
- Aplicação do algoritmo **K-Means** para agrupar clientes.  
- Determinação da melhor quantidade de clusters via método do cotovelo (*Elbow Method*) e *Silhouette Score*.  
- Interpretação dos grupos formados com base em métricas médias e perfis de consumo.

---

## 📈 Principais Insights

- Perfis de clientes com **alto valor médio de compra**, mas **baixa recorrência**, sugerem oportunidades de fidelização.  
- Segmentos mais lucrativos tendem a concentrar-se em **regiões específicas e faixas etárias médias**.  
- Descontos excessivos impactam negativamente a margem de lucro em determinados clusters.  
- A segmentação permite direcionar **campanhas personalizadas** e **estratégias de retenção**.

---

## 🧩 Tecnologias Utilizadas
- **Python**  
- **Pandas / NumPy** – manipulação e análise de dados  
- **Scikit-learn** – modelagem de aprendizado não supervisionado  
- **Matplotlib / Seaborn** – visualização de dados  
- **Jupyter Notebook** – ambiente de desenvolvimento e documentação  

---

## 📚 Fonte
Dataset: [E-commerce Sales Transactions Dataset – Kaggle](https://www.kaggle.com/datasets)

---

💡 *Este projeto faz parte de uma coleção de estudos voltados à aplicação prática de técnicas de Ciência de Dados, com foco em análise de comportamento do consumidor e insights de marketing.*
