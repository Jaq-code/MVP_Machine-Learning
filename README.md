# MVP Machine Learning & Analytics

**Autor:** Jaqueline Paciêlo Dantas  
**Matrícula:** 4052025000151  
**Dataset:** [Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)  

---

##  Sobre o Projeto

Este projeto tem como objetivo construir um modelo preditivo para **identificar clientes com alto risco de churn**.  
A análise ajuda a reduzir perdas e permite planejar ações de retenção de clientes.

- **Tipo de problema:** Classificação binária  
- **Benefício de negócio:** Redução de churn e otimização de estratégias de retenção  

---

##  Variáveis do Dataset

- **Categóricas:** gênero, tipo de contrato, forma de pagamento, serviços contratados  
- **Numéricas:** idade do cliente, tempo de assinatura, valor mensal pago  

---

## Metodologia

### 1️ Pré-processamento
- Limpeza de dados e tratamento de valores ausentes  
- Transformações de features com `StandardScaler` e `OneHotEncoder`  

### 2️ Análise Exploratória (EDA)
- Identificação de padrões relevantes para churn  

### 3️ Modelagem
- Comparação de modelos de classificação: Baseline, Regressão Logística e Random Forest  
- Ajuste de parâmetros para melhor performance  

### 4️ Avaliação
- Uso de métricas de performance e ajuste de thresholds para otimização  

---

## Tecnologias Utilizadas

- Python
- Pandas / NumPy
- Scikit-learn
- Matplotlib / Seaborn

---
