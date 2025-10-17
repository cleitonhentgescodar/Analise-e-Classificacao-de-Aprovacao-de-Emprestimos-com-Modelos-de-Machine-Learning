# 💰 Análise e Classificação de Aprovação de Empréstimos com Modelos de Machine Learning

Este projeto tem como objetivo analisar fatores financeiros e profissionais que influenciam a aprovação de solicitações de empréstimos, aplicando técnicas de **Machine Learning supervisionadas** para construir um modelo preditivo confiável e interpretável.

O estudo utiliza o **Loan Approval Dataset** (Kaggle), composto por **2.000 registros** e **8 variáveis**, incluindo informações sobre **renda anual (income)**, **pontuação de crédito (credit_score)**, **valor do empréstimo solicitado (loan_amount)**, **anos de emprego (years_employed)** e uma métrica adicional denominada **points**, que representa a pontuação geral de avaliação do solicitante.  
A variável-alvo **loan_approved** é booleana, indicando se o empréstimo foi **aprovado (True)** ou **rejeitado (False)**.

---

## 🚀 Objetivos

- Realizar **análise exploratória de dados (EDA)** para identificar padrões entre renda, pontuação de crédito e histórico de emprego.  
- Aplicar e comparar **modelos de classificação supervisionada**, incluindo:  
  - Logistic Regression  
  - Decision Tree  
  - Random Forest  
  - Support Vector Machine (SVM)  
  - K-Nearest Neighbors (KNN)  
  - XGBoost  
- Avaliar o desempenho dos modelos com base nas métricas **Acurácia**, **Precisão**, **Recall**, **F1-Score** e **Relatório de Classificação**.  
- Determinar os **atributos mais relevantes** que influenciam a decisão de aprovação de crédito.  
- Desenvolver um modelo preditivo que auxilie instituições financeiras a tomarem decisões mais rápidas e precisas.

---

## 🧠 Metodologia

### Pré-processamento dos dados
- Verificação e tratamento de valores ausentes e duplicados.  
- Padronização dos tipos de dados e normalização das variáveis numéricas.  
- Conversão da variável *loan_approved* para formato binário (0 = Rejeitado, 1 = Aprovado).  
- Divisão dos dados em **treino (70%)** e **teste (30%)** com `train_test_split`.

### Análise Exploratória (EDA)
- Visualização das distribuições de **income**, **credit_score** e **loan_amount**.  
- Análise de **correlação** entre as variáveis financeiras e o resultado da aprovação.  
- Identificação de **outliers** e padrões de aprovação entre diferentes faixas de renda e crédito.

### Modelagem e Avaliação
- Implementação dos modelos supervisionados: Logistic Regression, Decision Tree, Random Forest, SVM, KNN e XGBoost.  
- Aplicação de **validação cruzada (cross-validation)** para verificar a robustez dos resultados.  
- Comparação das métricas de desempenho (Acurácia, Precisão, Recall e F1-Score).  

---

## 📈 Principais Resultados

- A **pontuação de crédito (credit_score)** e a **renda (income)** foram os fatores mais determinantes na aprovação.  
- Clientes com **maior tempo de emprego (years_employed)** apresentaram maior probabilidade de aprovação.  
- Os modelos **Random Forest** e **XGBoost** apresentaram **melhor desempenho geral**.  
- A **Regressão Logística** se destacou por sua **facilidade de interpretação** e clareza dos coeficientes.  

---

## 🏁 Conclusão

Os resultados demonstram que modelos de **Machine Learning** podem ser ferramentas eficazes para **avaliar risco e apoiar decisões de crédito**.  
A integração de diferentes algoritmos e métricas permitiu identificar os principais fatores que influenciam a aprovação de empréstimos, proporcionando uma abordagem mais **precisa, rápida e escalável**.  
O projeto reforça o potencial da **inteligência artificial no setor financeiro**, otimizando processos e reduzindo vieses humanos em decisões de crédito.

---

## 🧩 Tecnologias Utilizadas

- **Python** (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, XGBoost)  
- **Jupyter Notebook**  
- **Random Forest**, **XGBoost**, **SVM**, **Decision Tree**, **KNN**, **Logistic Regression**  
- **Train/Test Split** e **Cross-Validation**

---

## 📚 Fonte

Dataset: [Loan Approval Dataset – Kaggle](https://www.kaggle.com/datasets/anishdevedward/loan-approval-dataset/code)

---

💡 Este projeto integra uma série de estudos sobre aplicações práticas de **Ciência de Dados e Machine Learning em finanças**, demonstrando como modelos preditivos podem aprimorar a análise de crédito e apoiar decisões estratégicas em instituições financeiras.
