# Fraud_Detection
Claro! Aqui está um modelo organizado de README para você colocar no seu repositório GitHub. Ajuste conforme suas preferências e conforme o contexto do seu projeto:

---

# Projeto de Classificação com Validação Cruzada e Comparação de Modelos de Machine Learning

## Descrição

Este projeto aplica e compara métodos de classificação utilizando diferentes algoritmos de machine learning, validação cruzada k-fold e otimização de hiperparâmetros via GridSearch. O objetivo é identificar o modelo com melhor desempenho em um conjunto de dados específico, avaliando também as métricas principais como matriz de confusão e curva ROC.

---

## Estrutura do Projeto

```
├── data/
│   └── dataset.csv
├── notebooks/
│   ├── 01_preprocessamento_e_exploracao.ipynb
│   ├── 02_modelos_e_treinamento.ipynb
│   ├── 03_comparacao_metricas.ipynb
├── src/
│   ├── models.py
│   ├── utils.py
├── README.md
├── requirements.txt
└── results/
    └── figuras/
```

---

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
   - Execute os notebooks na pasta `/notebooks` de acordo com o fluxo acima

---

## Resultados

- Visualização das matrizes de confusão de todos os modelos lado a lado
- Curva ROC comparativa entre os modelos
- Ranking dos modelos baseado em métricas de performance

---

## Exemplo de Imagens Geradas

*Insira aqui exemplos de matrizes de confusão, curva ROC, ou qualquer outro resultado visual relevante.*

---

## Requisitos

- Python >= 3.8  
- scikit-learn  
- matplotlib  
- pandas  
- xgboost  
- (adapte conforme sua necessidade)

---

## Referências

- [Scikit-learn Documentation](https://scikit-learn.org/stable/) {target="_blank"}
- [XGBoost Documentation](https://xgboost.readthedocs.io/en/stable/) {target="_blank"}

---

## Autor

Thayná Portella - (https://www.linkedin.com/thaynáportella)  
Contato: thayportellads@gmail.com

