# 📊 Segmentação de Clientes com Aprendizado Não Supervisionado (K-Means)

Este projeto aplica **técnicas de aprendizado de máquina não supervisionado** para identificar **padrões de comportamento de clientes em um e-commerce**. Utilizando o algoritmo **K-Means**, o estudo busca **segmentar consumidores com base em características de compra, rentabilidade e comportamento**, gerando insights que podem apoiar **estratégias de marketing, retenção e personalização de ofertas**.

O projeto utiliza o dataset **E-commerce Sales Transactions Dataset**, disponível no Kaggle, contendo milhares de registros de vendas com informações sobre clientes, categorias de produtos, descontos e métricas financeiras.

---

# 🎯 Objetivos

- Explorar padrões de consumo entre clientes de um e-commerce  
- Analisar métricas de desempenho como **lucro**, **descontos**, **volume de vendas** e **margens**  
- Criar **features derivadas** relevantes para análise de comportamento do consumidor  
- Aplicar **K-Means Clustering** para segmentação de clientes  
- Determinar o número ideal de clusters usando **Elbow Method** e **Silhouette Score**  
- Interpretar os clusters para identificar **perfis de clientes e oportunidades estratégicas de negócio**

---

# 🧠 Metodologia

## 1️⃣ Pré-processamento dos dados

Etapas realizadas para preparar os dados para modelagem:

- Remoção de **valores ausentes e registros duplicados**
- Criação de variáveis derivadas, como:
  - **Lucro percentual**
  - **Total gasto por cliente**
  - **Indicadores de comportamento de compra**
- Codificação de variáveis categóricas
- Padronização dos dados utilizando **StandardScaler**

Essas etapas garantem que os dados estejam adequados para algoritmos baseados em distância, como o **K-Means**.

---

## 2️⃣ Análise Exploratória de Dados (EDA)

Foi realizada uma análise exploratória para entender padrões de vendas e comportamento dos clientes:

- Distribuição de **lucro, descontos e volume de vendas**
- Comparação de desempenho entre **categorias de produtos**, **regiões** e **gênero**
- Análise temporal de **vendas e lucro**
- Identificação de possíveis **padrões de consumo e rentabilidade**

As visualizações foram construídas com **Matplotlib** e **Seaborn**.

---

## 3️⃣ Modelagem – Segmentação com K-Means

Para identificar grupos de clientes com comportamentos semelhantes, foi aplicado o algoritmo **K-Means**.

### Determinação do número ideal de clusters

Foram utilizados dois métodos:

**Elbow Method**

Analisa a redução da **inertia (SSE)** conforme o número de clusters aumenta.

**Silhouette Score**

Mede a qualidade da separação entre clusters.

A combinação dessas métricas permitiu definir o **número ideal de segmentos de clientes**.

---

# 📈 Principais Insights

A segmentação revelou diferentes perfis de clientes:

- **Clientes de alto valor**: alto ticket médio e maior contribuição para o lucro  
- **Clientes sensíveis a desconto**: compras frequentes, porém com margens menores  
- **Clientes ocasionais**: baixo volume de compras, mas com potencial de crescimento  

Outras observações importantes:

- Descontos elevados impactam negativamente a **margem de lucro em determinados segmentos**
- Alguns clusters apresentam **alto valor médio de compra, porém baixa recorrência**, indicando oportunidades de **programas de fidelização**
- Determinadas regiões concentram **segmentos mais rentáveis**, sugerindo oportunidades estratégicas de expansão

---

# 🧩 Tecnologias Utilizadas

- **Python**
- **Pandas** – manipulação e análise de dados
- **NumPy** – operações numéricas
- **Scikit-learn** – modelagem de machine learning
- **Matplotlib** – visualização de dados
- **Seaborn** – visualização estatística
- **Jupyter Notebook** – desenvolvimento e documentação do projeto

---

# 📊 Aplicações de Negócio

A segmentação de clientes permite:

- Criar **campanhas de marketing personalizadas**
- Melhorar estratégias de **retenção e fidelização**
- Identificar **clientes de alto valor**
- Otimizar políticas de **desconto e precificação**
- Apoiar decisões estratégicas de **expansão de mercado**

---

# 📚 Fonte dos Dados

Dataset: **E-commerce Sales Transactions Dataset**

Disponível em:  
https://www.kaggle.com/datasets

---

💡 *Este projeto faz parte de um portfólio de estudos focado na aplicação prática de técnicas de Ciência de Dados para análise de comportamento do consumidor e geração de insights estratégicos.*
