# Projeto de Classificação de Fraude com Validação Cruzada e Comparação de Modelos de Machine Learning

## Descrição

Este projeto aplica e compara métodos de classificação utilizando diferentes algoritmos de machine learning, validação cruzada k-fold e otimização de hiperparâmetros via GridSearch. O objetivo é identificar o modelo com melhor desempenho em um conjunto de dados específico, avaliando também as métricas principais como matriz de confusão e curva ROC.

---

## Estrutura do Projeto

```
├── data/
│   └── credit_card_fraud_10k.csv
├── notebooks/
│   ├── 01_preprocessamento_e_exploracao.ipynb
│   ├── 02_modelos_e_comparacao_metricas.ipynb
├── README.md
├── requirements.txt
└── results/
    └── figuras/
```

## Principais Etapas

1. **Pré-processamento**
   - Limpeza dos dados
   - Análise exploratória
   - Split em treino e teste

2. **Modelagem**
   - Decision Tree
   - Random Forest
   - KNN
   - Regressão Logística
   - XGBoost

3. **Otimização de Hiperparâmetros**
   - Utilização do GridSearchCV junto com validação cruzada (k-fold, k=5)

4. **Avaliação**
   - Matrizes de Confusão lado a lado
   - Curvas ROC comparativas
   - Relatórios de métricas (AUC, precisão, recall, F1-score)

---

## Como Reproduzir

1. **Clone o repositório**
   ```bash
   git clone https://github.com/thayportellads/fraud_detection.git
   cd fraud_detection
   ```

2. **Instale as dependências**
   ```bash
   pip install -r requirements.txt
   ```

3. **Adicione o(s) dataset(s)**
   - Coloque seu arquivo na pasta `/data`

4. **Notebooks**
   - Execute os notebooks de acordo com o fluxo acima

---

## Resultados

- Visualização das matrizes de confusão de todos os modelos lado a lado
- Curva ROC comparativa entre os modelos
- Ranking dos modelos baseado em métricas de performance

---

## Exemplo de Imagens Geradas

<img width="855" height="710" alt="image" src="https://github.com/user-attachments/assets/119423c5-2849-423a-9ff6-1e6dcd685b0f" />
<img width="2331" height="384" alt="image" src="https://github.com/user-attachments/assets/d003a5f5-2e58-46a5-8f0c-b694d3059abb" />
<img width="383" height="140" alt="image" src="https://github.com/user-attachments/assets/1f927e56-97fb-419a-a185-10f5345e1674" />

---

## Requisitos

- Python >= 3.8  
- scikit-learn  
- matplotlib  
- pandas  
- xgboost
- sklearn.ensemble
- sklearn.neighbors
- sklearn.tree
- sklearn.linear_model
- sklearn.metrics
- sklearn.model_selection
- sklearn.preprocessing
- sklearn.pipeline
- imblearn.over_sampling

---

## Referências

- [Scikit-learn Documentation](https://scikit-learn.org/stable/)
- [XGBoost Documentation](https://xgboost.readthedocs.io/en/stable/)

---

## Autor

Thayná Portella - (https://www.linkedin.com/thaynáportella)  
Contato: thayportellads@gmail.com

