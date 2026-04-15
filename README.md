# Credit Risk Modeling — Machine Learning

Projeto completo de modelagem de risco de crédito, cobrindo desde ingestão e tratamento de dados até treinamento, avaliação e interpretação de modelos preditivos.

> Objetivo: prever inadimplência e apoiar decisões de concessão de crédito com base em dados.

---

## Contexto de Negócio

Instituições financeiras precisam balancear **crescimento de carteira** com **controle de risco**.  
Este projeto simula um cenário real de concessão de crédito, respondendo:

- Quem tem maior probabilidade de inadimplência?
- Como reduzir risco sem sacrificar receita?
- Quais variáveis mais impactam o default?

---

## Pipeline de Dados

1. **Ingestão**
2. **Feature Engineering**
3. **Modelagem**
4. **Avaliação**
5. **Interpretação**

---

## Dataset

- Dados demográficos (idade, renda)
- Histórico financeiro
- Comportamento de crédito
- Target: inadimplência

---

## Modelos Utilizados

- Logistic Regression
- Random Forest
- Gradient Boosting

---

## Métricas de Avaliação

- Accuracy  
- Precision  
- Recall  
- AUC-ROC  

---

## Principais Insights

- Histórico de crédito é altamente preditivo  
- Trade-off entre recall e precisão  
- Modelos complexos performam melhor, mas são menos interpretáveis  

---

## Como Executar

```bash
git clone https://github.com/seu-usuario/credit-risk-model.git
pip install -r requirements.txt
jupyter notebook
```

---

## Stack Tecnológica

- Python
- Pandas / NumPy
- Scikit-learn
- Matplotlib / Seaborn

---

## Próximos Passos

- Deploy do modelo  
- Monitoramento de drift  
- Integração com pipeline de decisão  

---

## Diferenciais

- MachineLearning
- Foco em negócio  
